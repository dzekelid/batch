---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Batch Action Freeexclusivejob
  description: batch freeExclusiveJobAction action allows to get a generic BatchJob
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/batch/action/addBulkUploadResult:
    get:
      summary: Get Service Batch Action Addbulkuploadresult
      description: batch addBulkUploadResultAction action adds KalturaBulkUploadResult
        to the DB
      operationId: batch.addBulkUploadResult
      x-api-path-slug: servicebatchactionaddbulkuploadresult-get
      parameters:
      - in: query
        name: bulkUploadResult[accessControlProfileId]
      - in: query
        name: bulkUploadResult[action]
        description: 'Enum Type: `KalturaBulkUploadAction`'
      - in: query
        name: bulkUploadResult[appearInList]
      - in: query
        name: bulkUploadResult[bulkUploadJobId]
        description: The id of the parent job
      - in: query
        name: bulkUploadResult[bulkUploadResultObjectType]
        description: 'Enum Type: `KalturaBulkUploadObjectType`'
      - in: query
        name: bulkUploadResult[categoryId]
      - in: query
        name: bulkUploadResult[categoryReferenceId]
      - in: query
        name: bulkUploadResult[category]
      - in: query
        name: bulkUploadResult[city]
      - in: query
        name: bulkUploadResult[contentType]
      - in: query
        name: bulkUploadResult[contributionPolicy]
      - in: query
        name: bulkUploadResult[conversionProfileId]
      - in: query
        name: bulkUploadResult[country]
      - in: query
        name: bulkUploadResult[creatorId]
      - in: query
        name: bulkUploadResult[dateOfBirth]
      - in: query
        name: bulkUploadResult[defaultPermissionLevel]
      - in: query
        name: bulkUploadResult[description]
      - in: query
        name: bulkUploadResult[email]
      - in: query
        name: bulkUploadResult[entitledUsersEdit]
      - in: query
        name: bulkUploadResult[entitledUsersPublish]
      - in: query
        name: bulkUploadResult[entryId]
      - in: query
        name: bulkUploadResult[entryStatus]
      - in: query
        name: bulkUploadResult[errorCode]
      - in: query
        name: bulkUploadResult[errorDescription]
      - in: query
        name: bulkUploadResult[errorType]
      - in: query
        name: bulkUploadResult[firstName]
      - in: query
        name: bulkUploadResult[gender]
      - in: query
        name: bulkUploadResult[group]
      - in: query
        name: bulkUploadResult[inheritanceType]
      - in: query
        name: bulkUploadResult[lastName]
      - in: query
        name: bulkUploadResult[lineIndex]
        description: The index of the line in the CSV
      - in: query
        name: bulkUploadResult[moderation]
      - in: query
        name: bulkUploadResult[name]
      - in: query
        name: bulkUploadResult[objectErrorDescription]
      - in: query
        name: bulkUploadResult[objectId]
      - in: query
        name: bulkUploadResult[objectStatus]
      - in: query
        name: bulkUploadResult[objectType]
      - in: query
        name: bulkUploadResult[ownerId]
      - in: query
        name: bulkUploadResult[owner]
      - in: query
        name: bulkUploadResult[parentSystemName]
      - in: query
        name: bulkUploadResult[parentType]
      - in: query
        name: bulkUploadResult[partnerData]
      - in: query
        name: bulkUploadResult[partnerId]
      - in: query
        name: bulkUploadResult[partnerSortValue]
      - in: query
        name: bulkUploadResult[permissionLevel]
      - in: query
        name: bulkUploadResult[pluginsData]
      - in: query
        name: bulkUploadResult[privacy]
      - in: query
        name: bulkUploadResult[referenceId]
      - in: query
        name: bulkUploadResult[relativePath]
      - in: query
        name: bulkUploadResult[requiredObjectStatus]
      - in: query
        name: bulkUploadResult[resourceId]
      - in: query
        name: bulkUploadResult[rowData]
        description: The data as recieved in the csv
      - in: query
        name: bulkUploadResult[scheduleEndDate]
      - in: query
        name: bulkUploadResult[scheduleStartDate]
      - in: query
        name: bulkUploadResult[screenName]
      - in: query
        name: bulkUploadResult[sshKeyPassphrase]
      - in: query
        name: bulkUploadResult[sshPrivateKey]
      - in: query
        name: bulkUploadResult[sshPublicKey]
      - in: query
        name: bulkUploadResult[state]
      - in: query
        name: bulkUploadResult[status]
        description: 'Enum Type: `KalturaBulkUploadResultStatus`'
      - in: query
        name: bulkUploadResult[systemName]
      - in: query
        name: bulkUploadResult[tags]
      - in: query
        name: bulkUploadResult[templateEntryId]
      - in: query
        name: bulkUploadResult[thumbnailSaved]
      - in: query
        name: bulkUploadResult[thumbnailUrl]
      - in: query
        name: bulkUploadResult[title]
      - in: query
        name: bulkUploadResult[type]
      - in: query
        name: bulkUploadResult[updateMethod]
      - in: query
        name: bulkUploadResult[url]
      - in: query
        name: bulkUploadResult[userId]
      - in: query
        name: bulkUploadResult[userJoinPolicy]
      - in: query
        name: bulkUploadResult[zip]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - AddBulkUploadResult
  /service/batch/action/addMediaInfo:
    get:
      summary: Get Service Batch Action Addmediainfo
      description: batch addMediaInfoAction action saves a media info object
      operationId: batch.addMediaInfo
      x-api-path-slug: servicebatchactionaddmediainfo-get
      parameters:
      - in: query
        name: mediaInfo[audioBitRateMode]
        description: 'Enum Type: `KalturaBitRateMode`The audio bit rate mode'
      - in: query
        name: mediaInfo[audioBitRate]
        description: The audio bit rate
      - in: query
        name: mediaInfo[audioChannels]
        description: The number of audio channels
      - in: query
        name: mediaInfo[audioCodecId]
        description: The audio codec id
      - in: query
        name: mediaInfo[audioDuration]
        description: The audio duration
      - in: query
        name: mediaInfo[audioFormat]
        description: The audio format
      - in: query
        name: mediaInfo[audioResolution]
        description: The audio resolution
      - in: query
        name: mediaInfo[audioSamplingRate]
        description: The audio sampling rate
      - in: query
        name: mediaInfo[complexityValue]
      - in: query
        name: mediaInfo[containerBitRate]
        description: The container bit rate
      - in: query
        name: mediaInfo[containerDuration]
        description: The container duration
      - in: query
        name: mediaInfo[containerFormat]
        description: The container format
      - in: query
        name: mediaInfo[containerId]
        description: The container id
      - in: query
        name: mediaInfo[containerProfile]
        description: The container profile
      - in: query
        name: mediaInfo[contentStreams]
      - in: query
        name: mediaInfo[fileSize]
        description: The file size
      - in: query
        name: mediaInfo[flavorAssetId]
        description: The id of the related flavor asset
      - in: query
        name: mediaInfo[isFastStart]
      - in: query
        name: mediaInfo[maxGOP]
      - in: query
        name: mediaInfo[multiStreamInfo]
      - in: query
        name: mediaInfo[multiStream]
      - in: query
        name: mediaInfo[rawData]
        description: The data as returned by the mediainfo command line
      - in: query
        name: mediaInfo[scanType]
      - in: query
        name: mediaInfo[videoBitRateMode]
        description: 'Enum Type: `KalturaBitRateMode`The video bit rate mode'
      - in: query
        name: mediaInfo[videoBitRate]
        description: The video bit rate
      - in: query
        name: mediaInfo[videoCodecId]
        description: The video codec id
      - in: query
        name: mediaInfo[videoDar]
        description: The video display aspect ratio (dar)
      - in: query
        name: mediaInfo[videoDuration]
        description: The video duration
      - in: query
        name: mediaInfo[videoFormat]
        description: The video format
      - in: query
        name: mediaInfo[videoFrameRate]
        description: The video frame rate
      - in: query
        name: mediaInfo[videoHeight]
        description: The video height
      - in: query
        name: mediaInfo[videoRotation]
      - in: query
        name: mediaInfo[videoWidth]
        description: The video width
      - in: query
        name: mediaInfo[writingLib]
        description: The writing library
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - AddMediaInfo
  /service/batch/action/checkEntryIsDone:
    get:
      summary: Get Service Batch Action Checkentryisdone
      description: batch checkEntryIsDone Check weather a specified entry is done
        converting and changes it to ready.
      operationId: batch.checkEntryIsDone
      x-api-path-slug: servicebatchactioncheckentryisdone-get
      parameters:
      - in: query
        name: batchJobId
        description: The entry to check
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - CheckEntryIsDone
  /service/batch/action/checkFileExists:
    get:
      summary: Get Service Batch Action Checkfileexists
      description: batch checkFileExists action check if the file exists
      operationId: batch.checkFileExists
      x-api-path-slug: servicebatchactioncheckfileexists-get
      parameters:
      - in: query
        name: localPath
      - in: query
        name: No Name
      - in: query
        name: size
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - CheckFileExists
  /service/batch/action/cleanExclusiveJobs:
    get:
      summary: Get Service Batch Action Cleanexclusivejobs
      description: batch cleanExclusiveJobs action mark as fatal error all expired
        jobs
      operationId: batch.cleanExclusiveJobs
      x-api-path-slug: servicebatchactioncleanexclusivejobs-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - CleanExclusiveJobs
  /service/batch/action/countBulkUploadEntries:
    get:
      summary: Get Service Batch Action Countbulkuploadentries
      description: Returns total created entries count and total error entries count
      operationId: batch.countBulkUploadEntries
      x-api-path-slug: servicebatchactioncountbulkuploadentries-get
      parameters:
      - in: query
        name: bulkUploadJobId
        description: The id of the bulk upload job
      - in: query
        name: bulkUploadObjectType
        description: 'Enum Type: `KalturaBulkUploadObjectType`'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - CountBulkUploadEntries
  /service/batch/action/freeExclusiveJob:
    get:
      summary: Get Service Batch Action Freeexclusivejob
      description: batch freeExclusiveJobAction action allows to get a generic BatchJob
      operationId: batch.freeExclusiveJob
      x-api-path-slug: servicebatchactionfreeexclusivejob-get
      parameters:
      - in: query
        name: id
        description: The id of the job
      - in: query
        name: jobType
        description: 'Enum Type: `KalturaBatchJobType`The type of the job'
      - in: query
        name: lockKey[batchIndex]
      - in: query
        name: lockKey[schedulerId]
      - in: query
        name: lockKey[workerId]
      - in: query
        name: No Name
      - in: query
        name: resetExecutionAttempts
        description: Resets the job execution attampts to zero
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - FreeExclusiveJob
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
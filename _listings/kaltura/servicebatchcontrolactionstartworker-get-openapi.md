---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Batchcontrol Action Startworker
  description: batch start action starts a job
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
  /service/batch/action/getBulkUploadLastResult:
    get:
      summary: Get Service Batch Action Getbulkuploadlastresult
      description: batch getBulkUploadLastResultAction action returns the last result
        of the bulk upload
      operationId: batch.getBulkUploadLastResult
      x-api-path-slug: servicebatchactiongetbulkuploadlastresult-get
      parameters:
      - in: query
        name: bulkUploadJobId
        description: The id of the bulk upload job
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - GetBulkUploadLastResult
  /service/batch/action/getExclusiveAlmostDone:
    get:
      summary: Get Service Batch Action Getexclusivealmostdone
      description: batch getExclusiveAlmostDone action allows to get a BatchJob that
        wait for remote closure
      operationId: batch.getExclusiveAlmostDone
      x-api-path-slug: servicebatchactiongetexclusivealmostdone-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[batchVersionEqual]
      - in: query
        name: filter[batchVersionGreaterThanOrEqual]
      - in: query
        name: filter[batchVersionLessThanOrEqual]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[errNumberEqual]
      - in: query
        name: filter[errNumberIn]
      - in: query
        name: filter[errNumberNotIn]
      - in: query
        name: filter[errTypeEqual]
        description: 'Enum Type: `KalturaBatchJobErrorTypes`'
      - in: query
        name: filter[errTypeIn]
      - in: query
        name: filter[errTypeNotIn]
      - in: query
        name: filter[estimatedEffortGreaterThan]
      - in: query
        name: filter[estimatedEffortLessThan]
      - in: query
        name: filter[executionAttemptsGreaterThanOrEqual]
      - in: query
        name: filter[executionAttemptsLessThanOrEqual]
      - in: query
        name: filter[finishTimeGreaterThanOrEqual]
      - in: query
        name: filter[finishTimeLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idGreaterThanOrEqual]
      - in: query
        name: filter[jobSubTypeEqual]
      - in: query
        name: filter[jobSubTypeIn]
      - in: query
        name: filter[jobSubTypeNotIn]
      - in: query
        name: filter[jobTypeAndSubTypeIn]
      - in: query
        name: filter[jobTypeEqual]
        description: 'Enum Type: `KalturaBatchJobType`'
      - in: query
        name: filter[jobTypeIn]
      - in: query
        name: filter[jobTypeNotIn]
      - in: query
        name: filter[lockVersionGreaterThanOrEqual]
      - in: query
        name: filter[lockVersionLessThanOrEqual]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[partnerIdEqual]
      - in: query
        name: filter[partnerIdIn]
      - in: query
        name: filter[partnerIdNotIn]
      - in: query
        name: filter[priorityEqual]
      - in: query
        name: filter[priorityGreaterThanOrEqual]
      - in: query
        name: filter[priorityIn]
      - in: query
        name: filter[priorityLessThanOrEqual]
      - in: query
        name: filter[priorityNotIn]
      - in: query
        name: filter[queueTimeGreaterThanOrEqual]
      - in: query
        name: filter[queueTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaBatchJobStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[statusNotIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[urgencyGreaterThanOrEqual]
      - in: query
        name: filter[urgencyLessThanOrEqual]
      - in: query
        name: jobType
        description: 'Enum Type: `KalturaBatchJobType`The type of the job - could
          be a custom extended type'
      - in: query
        name: lockKey[batchIndex]
      - in: query
        name: lockKey[schedulerId]
      - in: query
        name: lockKey[workerId]
      - in: query
        name: maxExecutionTime
        description: The maximum time in seconds the job reguarly take
      - in: query
        name: No Name
      - in: query
        name: numberOfJobs
        description: The maximum number of jobs to return
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - GetExclusiveAlmostDone
  /service/batch/action/getExclusiveJobs:
    get:
      summary: Get Service Batch Action Getexclusivejobs
      description: batch getExclusiveJobsAction action allows to get a BatchJob
      operationId: batch.getExclusiveJobs
      x-api-path-slug: servicebatchactiongetexclusivejobs-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[batchVersionEqual]
      - in: query
        name: filter[batchVersionGreaterThanOrEqual]
      - in: query
        name: filter[batchVersionLessThanOrEqual]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[errNumberEqual]
      - in: query
        name: filter[errNumberIn]
      - in: query
        name: filter[errNumberNotIn]
      - in: query
        name: filter[errTypeEqual]
        description: 'Enum Type: `KalturaBatchJobErrorTypes`'
      - in: query
        name: filter[errTypeIn]
      - in: query
        name: filter[errTypeNotIn]
      - in: query
        name: filter[estimatedEffortGreaterThan]
      - in: query
        name: filter[estimatedEffortLessThan]
      - in: query
        name: filter[executionAttemptsGreaterThanOrEqual]
      - in: query
        name: filter[executionAttemptsLessThanOrEqual]
      - in: query
        name: filter[finishTimeGreaterThanOrEqual]
      - in: query
        name: filter[finishTimeLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idGreaterThanOrEqual]
      - in: query
        name: filter[jobSubTypeEqual]
      - in: query
        name: filter[jobSubTypeIn]
      - in: query
        name: filter[jobSubTypeNotIn]
      - in: query
        name: filter[jobTypeAndSubTypeIn]
      - in: query
        name: filter[jobTypeEqual]
        description: 'Enum Type: `KalturaBatchJobType`'
      - in: query
        name: filter[jobTypeIn]
      - in: query
        name: filter[jobTypeNotIn]
      - in: query
        name: filter[lockVersionGreaterThanOrEqual]
      - in: query
        name: filter[lockVersionLessThanOrEqual]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[partnerIdEqual]
      - in: query
        name: filter[partnerIdIn]
      - in: query
        name: filter[partnerIdNotIn]
      - in: query
        name: filter[priorityEqual]
      - in: query
        name: filter[priorityGreaterThanOrEqual]
      - in: query
        name: filter[priorityIn]
      - in: query
        name: filter[priorityLessThanOrEqual]
      - in: query
        name: filter[priorityNotIn]
      - in: query
        name: filter[queueTimeGreaterThanOrEqual]
      - in: query
        name: filter[queueTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaBatchJobStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[statusNotIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[urgencyGreaterThanOrEqual]
      - in: query
        name: filter[urgencyLessThanOrEqual]
      - in: query
        name: jobType
        description: 'Enum Type: `KalturaBatchJobType`The type of the job - could
          be a custom extended type'
      - in: query
        name: lockKey[batchIndex]
      - in: query
        name: lockKey[schedulerId]
      - in: query
        name: lockKey[workerId]
      - in: query
        name: maxExecutionTime
        description: The maximum time in seconds the job reguarly take
      - in: query
        name: maxJobToPullForCache
        description: The number of job to pull to cache
      - in: query
        name: No Name
      - in: query
        name: numberOfJobs
        description: The maximum number of jobs to return
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - GetExclusiveJobs
  /service/batch/action/getExclusiveNotificationJobs:
    get:
      summary: Get Service Batch Action Getexclusivenotificationjobs
      description: batch getExclusiveNotificationJob action allows to get a BatchJob
        of type NOTIFICATION
      operationId: batch.getExclusiveNotificationJobs
      x-api-path-slug: servicebatchactiongetexclusivenotificationjobs-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[batchVersionEqual]
      - in: query
        name: filter[batchVersionGreaterThanOrEqual]
      - in: query
        name: filter[batchVersionLessThanOrEqual]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[errNumberEqual]
      - in: query
        name: filter[errNumberIn]
      - in: query
        name: filter[errNumberNotIn]
      - in: query
        name: filter[errTypeEqual]
        description: 'Enum Type: `KalturaBatchJobErrorTypes`'
      - in: query
        name: filter[errTypeIn]
      - in: query
        name: filter[errTypeNotIn]
      - in: query
        name: filter[estimatedEffortGreaterThan]
      - in: query
        name: filter[estimatedEffortLessThan]
      - in: query
        name: filter[executionAttemptsGreaterThanOrEqual]
      - in: query
        name: filter[executionAttemptsLessThanOrEqual]
      - in: query
        name: filter[finishTimeGreaterThanOrEqual]
      - in: query
        name: filter[finishTimeLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idGreaterThanOrEqual]
      - in: query
        name: filter[jobSubTypeEqual]
      - in: query
        name: filter[jobSubTypeIn]
      - in: query
        name: filter[jobSubTypeNotIn]
      - in: query
        name: filter[jobTypeAndSubTypeIn]
      - in: query
        name: filter[jobTypeEqual]
        description: 'Enum Type: `KalturaBatchJobType`'
      - in: query
        name: filter[jobTypeIn]
      - in: query
        name: filter[jobTypeNotIn]
      - in: query
        name: filter[lockVersionGreaterThanOrEqual]
      - in: query
        name: filter[lockVersionLessThanOrEqual]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[partnerIdEqual]
      - in: query
        name: filter[partnerIdIn]
      - in: query
        name: filter[partnerIdNotIn]
      - in: query
        name: filter[priorityEqual]
      - in: query
        name: filter[priorityGreaterThanOrEqual]
      - in: query
        name: filter[priorityIn]
      - in: query
        name: filter[priorityLessThanOrEqual]
      - in: query
        name: filter[priorityNotIn]
      - in: query
        name: filter[queueTimeGreaterThanOrEqual]
      - in: query
        name: filter[queueTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaBatchJobStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[statusNotIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[urgencyGreaterThanOrEqual]
      - in: query
        name: filter[urgencyLessThanOrEqual]
      - in: query
        name: lockKey[batchIndex]
      - in: query
        name: lockKey[schedulerId]
      - in: query
        name: lockKey[workerId]
      - in: query
        name: maxExecutionTime
        description: The maximum time in seconds the job reguarly take
      - in: query
        name: No Name
      - in: query
        name: numberOfJobs
        description: The maximum number of jobs to return
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - GetExclusiveNotificationJobs
  /service/batch/action/getQueueSize:
    get:
      summary: Get Service Batch Action Getqueuesize
      description: batch getQueueSize action get the queue size for job type
      operationId: batch.getQueueSize
      x-api-path-slug: servicebatchactiongetqueuesize-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: workerQueueFilter[filter][advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][categoriesMatchOr]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][categoryEntryStatusIn]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][categoryIdEqual]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][contentLike]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][contentMultiLikeAnd]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][contentMultiLikeOr]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][cuePointsFreeText]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][cuePointTypeIn]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][depthGreaterThanEqual]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][distributionProfileId]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: workerQueueFilter[filter][advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][extendedStatusIn]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][field]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][idEqual]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][idIn]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][indexIdGreaterThan]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][items]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][memberIdEq]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][memberIdIn]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][metadataProfileId]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][noDistributionProfiles]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][not]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][objectType]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: workerQueueFilter[filter][advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][userIdEqual]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][userIdIn]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][value]
      - in: query
        name: workerQueueFilter[filter][advancedSearch][watermarkId]
      - in: query
        name: workerQueueFilter[filter][batchVersionEqual]
      - in: query
        name: workerQueueFilter[filter][batchVersionGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][batchVersionLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][createdAtGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][createdAtLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][entryIdEqual]
      - in: query
        name: workerQueueFilter[filter][errNumberEqual]
      - in: query
        name: workerQueueFilter[filter][errNumberIn]
      - in: query
        name: workerQueueFilter[filter][errNumberNotIn]
      - in: query
        name: workerQueueFilter[filter][errTypeEqual]
        description: 'Enum Type: `KalturaBatchJobErrorTypes`'
      - in: query
        name: workerQueueFilter[filter][errTypeIn]
      - in: query
        name: workerQueueFilter[filter][errTypeNotIn]
      - in: query
        name: workerQueueFilter[filter][estimatedEffortGreaterThan]
      - in: query
        name: workerQueueFilter[filter][estimatedEffortLessThan]
      - in: query
        name: workerQueueFilter[filter][executionAttemptsGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][executionAttemptsLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][finishTimeGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][finishTimeLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][idEqual]
      - in: query
        name: workerQueueFilter[filter][idGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][jobSubTypeEqual]
      - in: query
        name: workerQueueFilter[filter][jobSubTypeIn]
      - in: query
        name: workerQueueFilter[filter][jobSubTypeNotIn]
      - in: query
        name: workerQueueFilter[filter][jobTypeAndSubTypeIn]
      - in: query
        name: workerQueueFilter[filter][jobTypeEqual]
        description: 'Enum Type: `KalturaBatchJobType`'
      - in: query
        name: workerQueueFilter[filter][jobTypeIn]
      - in: query
        name: workerQueueFilter[filter][jobTypeNotIn]
      - in: query
        name: workerQueueFilter[filter][lockVersionGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][lockVersionLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][objectType]
      - in: query
        name: workerQueueFilter[filter][orderBy]
      - in: query
        name: workerQueueFilter[filter][partnerIdEqual]
      - in: query
        name: workerQueueFilter[filter][partnerIdIn]
      - in: query
        name: workerQueueFilter[filter][partnerIdNotIn]
      - in: query
        name: workerQueueFilter[filter][priorityEqual]
      - in: query
        name: workerQueueFilter[filter][priorityGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][priorityIn]
      - in: query
        name: workerQueueFilter[filter][priorityLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][priorityNotIn]
      - in: query
        name: workerQueueFilter[filter][queueTimeGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][queueTimeLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][statusEqual]
        description: 'Enum Type: `KalturaBatchJobStatus`'
      - in: query
        name: workerQueueFilter[filter][statusIn]
      - in: query
        name: workerQueueFilter[filter][statusNotIn]
      - in: query
        name: workerQueueFilter[filter][updatedAtGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][updatedAtLessThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][urgencyGreaterThanOrEqual]
      - in: query
        name: workerQueueFilter[filter][urgencyLessThanOrEqual]
      - in: query
        name: workerQueueFilter[jobType]
        description: 'Enum Type: `KalturaBatchJobType`'
      - in: query
        name: workerQueueFilter[schedulerId]
      - in: query
        name: workerQueueFilter[workerId]
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - GetQueueSize
  /service/batch/action/logConversion:
    get:
      summary: Get Service Batch Action Logconversion
      description: Add the data to the flavor asset conversion log, creates it if
        doesn't exists
      operationId: batch.logConversion
      x-api-path-slug: servicebatchactionlogconversion-get
      parameters:
      - in: query
        name: data
      - in: query
        name: flavorAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - LogConversion
  /service/batch/action/resetJobExecutionAttempts:
    get:
      summary: Get Service Batch Action Resetjobexecutionattempts
      description: batch resetJobExecutionAttempts action resets the execution attempts
        of the job
      operationId: batch.resetJobExecutionAttempts
      x-api-path-slug: servicebatchactionresetjobexecutionattempts-get
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
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - ResetJobExecutionAttempts
  /service/batch/action/suspendJobs:
    get:
      summary: Get Service Batch Action Suspendjobs
      description: batch suspendJobs action suspends jobs from running.
      operationId: batch.suspendJobs
      x-api-path-slug: servicebatchactionsuspendjobs-get
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
      - SuspendJobs
  /service/batch/action/updateBulkUploadResults:
    get:
      summary: Get Service Batch Action Updatebulkuploadresults
      description: batch updateBulkUploadResults action adds KalturaBulkUploadResult
        to the DB
      operationId: batch.updateBulkUploadResults
      x-api-path-slug: servicebatchactionupdatebulkuploadresults-get
      parameters:
      - in: query
        name: bulkUploadJobId
        description: The id of the bulk upload job
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - UpdateBulkUploadResults
  /service/batch/action/updateExclusiveConvertCollectionJob:
    get:
      summary: Get Service Batch Action Updateexclusiveconvertcollectionjob
      description: batch updateExclusiveConvertCollectionJobAction action updates
        a BatchJob of type CONVERT_PROFILE that was claimed using the getExclusiveConvertJobs
      operationId: batch.updateExclusiveConvertCollectionJob
      x-api-path-slug: servicebatchactionupdateexclusiveconvertcollectionjob-get
      parameters:
      - in: query
        name: id
        description: The id of the job to free
      - in: query
        name: job[data][actualSrcFileSyncLocalPath]
        description: The translated path as used by the scheduler
      - in: query
        name: job[data][addedPrivacyContexts]
      - in: query
        name: job[data][amfArray]
        description: amf Array File Path
      - in: query
        name: job[data][assetId]
      - in: query
        name: job[data][authenticationMethod]
        description: 'Enum Type: `KalturaHttpNotificationAuthenticationMethod`The
          HTTP authentication method to use'
      - in: query
        name: job[data][backupEncoderIP]
      - in: query
        name: job[data][backupStreamID]
      - in: query
        name: job[data][bodyParams]
      - in: query
        name: job[data][cachedObjectType]
        description: Class name
      - in: query
        name: job[data][calculateComplexity]
      - in: query
        name: job[data][campaignId]
      - in: query
        name: job[data][captionAssetId]
      - in: query
        name: job[data][categoryId]
        description: category id
      - in: query
        name: job[data][changedCategoryId]
      - in: query
        name: job[data][columns]
      - in: query
        name: job[data][commandLinesStr]
      - in: query
        name: job[data][concatenatedDuration]
        description: duration of the concated video
      - in: query
        name: job[data][connectTimeout]
        description: The number of seconds to wait while trying to connect
      - in: query
        name: job[data][contentMatchPolicy]
        description: 'Enum Type: `KalturaDropFolderContentFileHandlerMatchPolicy`'
      - in: query
        name: job[data][contentMoid]
        description: Unique Kontiki MOID for the content uploaded to Kontiki
      - in: query
        name: job[data][contentParameters]
      - in: query
        name: job[data][conversionProfileId]
      - in: query
        name: job[data][cpcode]
      - in: query
        name: job[data][createLink]
      - in: query
        name: job[data][createThumb]
        description: Indicates if a thumbnail should be created
      - in: query
        name: job[data][customData]
      - in: query
        name: job[data][customHeaders]
      - in: query
        name: job[data][data]
      - in: query
        name: job[data][deletedPrivacyContexts]
      - in: query
        name: job[data][description]
      - in: query
        name: job[data][destCategoryFullIds]
        description: Destination categories fallback ids
      - in: query
        name: job[data][destCategoryId]
        description: Destination category id
      - in: query
        name: job[data][destDataFilePath]
        description: The data output file
      - in: query
        name: job[data][destDirLocalPath]
      - in: query
        name: job[data][destDirRemoteUrl]
      - in: query
        name: job[data][destFileLocalPath]
      - in: query
        name: job[data][destFileName]
      - in: query
        name: job[data][destFilePath]
        description: Output file
      - in: query
        name: job[data][destFileSyncLocalPath]
      - in: query
        name: job[data][destFileSyncRemoteUrl]
      - in: query
        name: job[data][destFileSyncStoredPath]
      - in: query
        name: job[data][destVersion]
      - in: query
        name: job[data][destXsdPath]
      - in: query
        name: job[data][detectGOP]
      - in: query
        name: job[data][distributionProfileId]
      - in: query
        name: job[data][distributionProfile][accountId]
      - in: query
        name: job[data][distributionProfile][adFreeApplicationGuid]
        description: The GUID for the application in which to record metrics and enforce
          business rules obtained through your Unicorn representative
      - in: query
        name: job[data][distributionProfile][adServerPartnerId]
      - in: query
        name: job[data][distributionProfile][allowAdsenseForVideo]
      - in: query
        name: job[data][distributionProfile][allowComments]
      - in: query
        name: job[data][distributionProfile][allowDownload]
      - in: query
        name: job[data][distributionProfile][allowEmbedding]
      - in: query
        name: job[data][distributionProfile][allowInvideo]
      - in: query
        name: job[data][distributionProfile][allowMidRollAds]
      - in: query
        name: job[data][distributionProfile][allowPostRollAds]
      - in: query
        name: job[data][distributionProfile][allowPreRollAds]
      - in: query
        name: job[data][distributionProfile][allowRatings]
      - in: query
        name: job[data][distributionProfile][allowResponses]
      - in: query
        name: job[data][distributionProfile][allowStreaming]
      - in: query
        name: job[data][distributionProfile][allowSyndication]
      - in: query
        name: job[data][distributionProfile][apiAuthorizeUrl]
      - in: query
        name: job[data][distributionProfile][apiHostUrl]
        description: The API host URL that the Upload User should have access to,
          Used for HTTP content submission
      - in: query
        name: job[data][distributionProfile][apikey]
      - in: query
        name: job[data][distributionProfile][asperaHost]
      - in: query
        name: job[data][distributionProfile][asperaLogin]
      - in: query
        name: job[data][distributionProfile][asperaPass]
      - in: query
        name: job[data][distributionProfile][asperaPrivateKey]
      - in: query
        name: job[data][distributionProfile][asperaPublicKey]
      - in: query
        name: job[data][distributionProfile][assetFilenameXslt]
      - in: query
        name: job[data][distributionProfile][assumeSuccess]
      - in: query
        name: job[data][distributionProfile][autoCreateFlavors]
        description: Comma separated flavor params ids that should be auto converted
      - in: query
        name: job[data][distributionProfile][autoCreateThumb]
        description: Comma separated thumbnail params ids that should be auto generated
      - in: query
        name: job[data][distributionProfile][backgroundImageStandard]
      - in: query
        name: job[data][distributionProfile][backgroundImageWide]
      - in: query
        name: job[data][distributionProfile][basePath]
      - in: query
        name: job[data][distributionProfile][blockOutsideOwnership]
      - in: query
        name: job[data][distributionProfile][bodyXslt]
      - in: query
        name: job[data][distributionProfile][captionAutosync]
      - in: query
        name: job[data][distributionProfile][categoryId]
      - in: query
        name: job[data][distributionProfile][certificateKey]
      - in: query
        name: job[data][distributionProfile][channelCopyright]
      - in: query
        name: job[data][distributionProfile][channelDescription]
      - in: query
        name: job[data][distributionProfile][channelGenerator]
      - in: query
        name: job[data][distributionProfile][channelGuid]
        description: The Channel GUID assigned to this Publication Rule
      - in: query
        name: job[data][distributionProfile][channelImageHeight]
      - in: query
        name: job[data][distributionProfile][channelImageLink]
      - in: query
        name: job[data][distributionProfile][channelImageTitle]
      - in: query
        name: job[data][distributionProfile][channelImageUrl]
      - in: query
        name: job[data][distributionProfile][channelImageWidth]
      - in: query
        name: job[data][distributionProfile][channelLanguage]
      - in: query
        name: job[data][distributionProfile][channelLink]
      - in: query
        name: job[data][distributionProfile][channelManagingEditor]
      - in: query
        name: job[data][distributionProfile][channelRating]
      - in: query
        name: job[data][distributionProfile][channelTitle]
      - in: query
        name: job[data][distributionProfile][claimType]
      - in: query
        name: job[data][distributionProfile][commercialPolicy]
      - in: query
        name: job[data][distributionProfile][contactEmail]
      - in: query
        name: job[data][distributionProfile][contactTelephone]
      - in: query
        name: job[data][distributionProfile][contentOwner]
      - in: query
        name: job[data][distributionProfile][copyright]
      - in: query
        name: job[data][distributionProfile][cPlatformTvSeriesField]
      - in: query
        name: job[data][distributionProfile][cPlatformTvSeries]
      - in: query
        name: job[data][distributionProfile][csId]
      - in: query
        name: job[data][distributionProfile][cuePointsProvider]
      - in: query
        name: job[data][distributionProfile][defaultCategory]
      - in: query
        name: job[data][distributionProfile][deleteEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][deleteReference]
      - in: query
        name: job[data][distributionProfile][disableEpisodeNumberCustomValidation]
      - in: query
        name: job[data][distributionProfile][disableMetadata]
      - in: query
        name: job[data][distributionProfile][distributeCaptions]
      - in: query
        name: job[data][distributionProfile][distributeCuePoints]
      - in: query
        name: job[data][distributionProfile][distributeRemoteCaptionAssetContent]
      - in: query
        name: job[data][distributionProfile][distributeRemoteFlavorAssetContent]
      - in: query
        name: job[data][distributionProfile][distributeRemoteThumbAssetContent]
      - in: query
        name: job[data][distributionProfile][domainGuid]
        description: The GUID of the Customer Domain in the Unicorn system obtained
          by contacting your Unicorn representative
      - in: query
        name: job[data][distributionProfile][domainName]
        description: The name of the Domain that the Upload User should have access
          to, Used for authentication
      - in: query
        name: job[data][distributionProfile][domain]
      - in: query
        name: job[data][distributionProfile][downloadPriceCode]
      - in: query
        name: job[data][distributionProfile][email]
      - in: query
        name: job[data][distributionProfile][enableAdServer]
      - in: query
        name: job[data][distributionProfile][entitlements]
      - in: query
        name: job[data][distributionProfile][entitlement]
      - in: query
        name: job[data][distributionProfile][feedAuthorName]
      - in: query
        name: job[data][distributionProfile][feedCopyright]
      - in: query
        name: job[data][distributionProfile][feedDescription]
      - in: query
        name: job[data][distributionProfile][feedImageHeight]
      - in: query
        name: job[data][distributionProfile][feedImageLink]
      - in: query
        name: job[data][distributionProfile][feedImageTitle]
      - in: query
        name: job[data][distributionProfile][feedImageUrl]
      - in: query
        name: job[data][distributionProfile][feedImageWidth]
      - in: query
        name: job[data][distributionProfile][feedLanguage]
      - in: query
        name: job[data][distributionProfile][feedLastBuildDate]
      - in: query
        name: job[data][distributionProfile][feedLink]
      - in: query
        name: job[data][distributionProfile][feedSpecVersion]
        description: 'Enum Type: `KalturaYouTubeDistributionFeedSpecVersion`'
      - in: query
        name: job[data][distributionProfile][feedSubtitle]
      - in: query
        name: job[data][distributionProfile][feedTitle]
      - in: query
        name: job[data][distributionProfile][fieldConfigArray]
      - in: query
        name: job[data][distributionProfile][flavorAssetFilenameXslt]
      - in: query
        name: job[data][distributionProfile][flvFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][ftpHost]
      - in: query
        name: job[data][distributionProfile][ftpLogin]
      - in: query
        name: job[data][distributionProfile][ftpPassword]
      - in: query
        name: job[data][distributionProfile][ftpPass]
      - in: query
        name: job[data][distributionProfile][ftpPath]
      - in: query
        name: job[data][distributionProfile][ftpUsername]
      - in: query
        name: job[data][distributionProfile][genericProviderId]
        description: '`insertOnly`'
      - in: query
        name: job[data][distributionProfile][geoBlockingMapping]
        description: 'Enum Type: `KalturaDailymotionGeoBlockingMapping`'
      - in: query
        name: job[data][distributionProfile][googleClientId]
      - in: query
        name: job[data][distributionProfile][googleClientSecret]
      - in: query
        name: job[data][distributionProfile][googleTokenData]
      - in: query
        name: job[data][distributionProfile][hideViewCount]
      - in: query
        name: job[data][distributionProfile][host]
      - in: query
        name: job[data][distributionProfile][ignoreSchedulingInFeed]
      - in: query
        name: job[data][distributionProfile][ingestUrl]
      - in: query
        name: job[data][distributionProfile][instreamStandard]
      - in: query
        name: job[data][distributionProfile][instreamTrueview]
      - in: query
        name: job[data][distributionProfile][ips]
      - in: query
        name: job[data][distributionProfile][itemLink]
      - in: query
        name: job[data][distributionProfile][itemMediaRating]
      - in: query
        name: job[data][distributionProfile][itemsPerPage]
      - in: query
        name: job[data][distributionProfile][itemType]
      - in: query
        name: job[data][distributionProfile][itemXpathsToExtend]
      - in: query
        name: job[data][distributionProfile][mapAccessControlProfileIds]
      - in: query
        name: job[data][distributionProfile][mapCaptionParamsIds]
      - in: query
        name: job[data][distributionProfile][mapConversionProfileIds]
      - in: query
        name: job[data][distributionProfile][mapFlavorParamsIds]
      - in: query
        name: job[data][distributionProfile][mapMetadataProfileIds]
      - in: query
        name: job[data][distributionProfile][mapStorageProfileIds]
      - in: query
        name: job[data][distributionProfile][mapThumbParamsIds]
      - in: query
        name: job[data][distributionProfile][metadataFilenameXslt]
      - in: query
        name: job[data][distributionProfile][metadataProfileId]
      - in: query
        name: job[data][distributionProfile][metadataXpathsTriggerUpdate]
      - in: query
        name: job[data][distributionProfile][metadataXslt]
      - in: query
        name: job[data][distributionProfile][msnvideoCat]
      - in: query
        name: job[data][distributionProfile][msnvideoTopCat]
      - in: query
        name: job[data][distributionProfile][msnvideoTop]
      - in: query
        name: job[data][distributionProfile][name]
      - in: query
        name: job[data][distributionProfile][notificationEmail]
      - in: query
        name: job[data][distributionProfile][objectType]
      - in: query
        name: job[data][distributionProfile][optionalAssetDistributionRules]
      - in: query
        name: job[data][distributionProfile][optionalFlavorParamsIds]
        description: Comma separated flavor params ids that should be submitted if
          ready
      - in: query
        name: job[data][distributionProfile][optionalThumbDimensions]
      - in: query
        name: job[data][distributionProfile][overrideManualEdits]
      - in: query
        name: job[data][distributionProfile][ownerName]
      - in: query
        name: job[data][distributionProfile][pageAccessToken]
      - in: query
        name: job[data][distributionProfile][pageGroup]
      - in: query
        name: job[data][distributionProfile][pageId]
      - in: query
        name: job[data][distributionProfile][passphrase]
      - in: query
        name: job[data][distributionProfile][password]
      - in: query
        name: job[data][distributionProfile][permissions]
      - in: query
        name: job[data][distributionProfile][port]
      - in: query
        name: job[data][distributionProfile][priority]
      - in: query
        name: job[data][distributionProfile][privacyStatus]
      - in: query
        name: job[data][distributionProfile][processFeed]
        description: 'Enum Type: `KalturaYahooDistributionProcessFeedActionStatus`'
      - in: query
        name: job[data][distributionProfile][protocol]
        description: '`insertOnly`Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: job[data][distributionProfile][providerId]
      - in: query
        name: job[data][distributionProfile][providerName]
      - in: query
        name: job[data][distributionProfile][providerType]
        description: '`insertOnly`Enum Type: `KalturaDistributionProviderType`'
      - in: query
        name: job[data][distributionProfile][rating]
      - in: query
        name: job[data][distributionProfile][recommendedDcForDownload]
        description: The best Kaltura data center to be used to download the asset
          files to
      - in: query
        name: job[data][distributionProfile][recommendedDcForExecute]
        description: The best Kaltura data center to be used to execute the distribution
          job
      - in: query
        name: job[data][distributionProfile][recommendedStorageProfileForDownload]
        description: The best external storage to be used to download the asset files
          from
      - in: query
        name: job[data][distributionProfile][releaseClaims]
      - in: query
        name: job[data][distributionProfile][remoteAssetParamsId]
        description: The flavor-params that will be used for the remote asset
      - in: query
        name: job[data][distributionProfile][replaceAirDates]
      - in: query
        name: job[data][distributionProfile][replaceGroup]
      - in: query
        name: job[data][distributionProfile][reportEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][requiredAssetDistributionRules]
      - in: query
        name: job[data][distributionProfile][requiredFlavorParamsIds]
        description: Comma separated flavor params ids that required to be ready before
          submission
      - in: query
        name: job[data][distributionProfile][requiredThumbDimensions]
      - in: query
        name: job[data][distributionProfile][reRequestPermissions]
      - in: query
        name: job[data][distributionProfile][seasonNumber]
      - in: query
        name: job[data][distributionProfile][seasonSynopsis]
      - in: query
        name: job[data][distributionProfile][seasonTuneInInformation]
      - in: query
        name: job[data][distributionProfile][sendMetadataAfterAssets]
      - in: query
        name: job[data][distributionProfile][seriesAdditionalCategories]
      - in: query
        name: job[data][distributionProfile][seriesChannel]
      - in: query
        name: job[data][distributionProfile][seriesPrimaryCategory]
      - in: query
        name: job[data][distributionProfile][sftpBaseDir]
      - in: query
        name: job[data][distributionProfile][sftpBasePath]
      - in: query
        name: job[data][distributionProfile][sftpHost]
      - in: query
        name: job[data][distributionProfile][sftpLogin]
      - in: query
        name: job[data][distributionProfile][sftpPass]
      - in: query
        name: job[data][distributionProfile][sftpPort]
      - in: query
        name: job[data][distributionProfile][sftpPrivateKey]
      - in: query
        name: job[data][distributionProfile][sftpPublicKey]
      - in: query
        name: job[data][distributionProfile][shouldAddThumbExtension]
      - in: query
        name: job[data][distributionProfile][shouldIncludeCaptions]
      - in: query
        name: job[data][distributionProfile][shouldIncludeCuePoints]
      - in: query
        name: job[data][distributionProfile][slFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][slHdFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][sourceFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][sourceFriendlyName]
      - in: query
        name: job[data][distributionProfile][source]
      - in: query
        name: job[data][distributionProfile][state]
      - in: query
        name: job[data][distributionProfile][status]
        description: 'Enum Type: `KalturaDistributionProfileStatus`'
      - in: query
        name: job[data][distributionProfile][storageProfileId]
        description: The remote storage that should be used for the remote asset
      - in: query
        name: job[data][distributionProfile][streamingPriceCode]
      - in: query
        name: job[data][distributionProfile][strict]
      - in: query
        name: job[data][distributionProfile][submitAction][ftpPassiveMode]
      - in: query
        name: job[data][distributionProfile][submitAction][httpFieldName]
      - in: query
        name: job[data][distributionProfile][submitAction][httpFileName]
      - in: query
        name: job[data][distributionProfile][submitAction][password]
      - in: query
        name: job[data][distributionProfile][submitAction][protocol]
        description: 'Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: job[data][distributionProfile][submitAction][serverPath]
      - in: query
        name: job[data][distributionProfile][submitAction][serverUrl]
      - in: query
        name: job[data][distributionProfile][submitAction][username]
      - in: query
        name: job[data][distributionProfile][submitEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][sunriseDefaultOffset]
        description: If entry distribution sunrise not specified that will be the
          default since entry creation time, in seconds
      - in: query
        name: job[data][distributionProfile][sunsetDefaultOffset]
        description: If entry distribution sunset not specified that will be the default
          since entry creation time, in seconds
      - in: query
        name: job[data][distributionProfile][tags]
      - in: query
        name: job[data][distributionProfile][targetAccountId]
      - in: query
        name: job[data][distributionProfile][targetLoginId]
      - in: query
        name: job[data][distributionProfile][targetLoginPassword]
      - in: query
        name: job[data][distributionProfile][targetServiceUrl]
      - in: query
        name: job[data][distributionProfile][target]
      - in: query
        name: job[data][distributionProfile][thumbnailAssetFilenameXslt]
      - in: query
        name: job[data][distributionProfile][ugcPolicy]
      - in: query
        name: job[data][distributionProfile][updateEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][upstreamNetworkId]
      - in: query
        name: job[data][distributionProfile][upstreamNetworkName]
      - in: query
        name: job[data][distributionProfile][upstreamVideoId]
      - in: query
        name: job[data][distributionProfile][urgentReference]
      - in: query
        name: job[data][distributionProfile][useCategoryEntries]
        description: When checking custom XSLT conditions using the fieldConfigArray
          - address only categories associated with the entry via the categoryEntry
          object
      - in: query
        name: job[data][distributionProfile][userAccessToken]
      - in: query
        name: job[data][distributionProfile][username]
      - in: query
        name: job[data][distributionProfile][user]
      - in: query
        name: job[data][distributionProfile][videoMediaType]
      - in: query
        name: job[data][distributionProfile][wmvFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][xsltFile]
      - in: query
        name: job[data][distributionProfile][xsl]
      - in: query
        name: job[data][domainName]
      - in: query
        name: job[data][dropFolderFileIds]
      - in: query
        name: job[data][dropFolderFileId]
      - in: query
        name: job[data][dropFolderId]
      - in: query
        name: job[data][duration]
        description: Clipping duration in seconds
      - in: query
        name: job[data][dvrEnabled]
        description: 'Enum Type: `KalturaDVRStatus`'
      - in: query
        name: job[data][dvrWindow]
      - in: query
        name: job[data][emailId]
      - in: query
        name: job[data][encoderIP]
      - in: query
        name: job[data][encoderPassword]
      - in: query
        name: job[data][encoderUsername]
      - in: query
        name: job[data][endDate]
      - in: query
        name: job[data][endObjectKey]
      - in: query
        name: job[data][endPoint]
      - in: query
        name: job[data][endTime]
        description: Duration of the live entry including all recorded segments including
          the current
      - in: query
        name: job[data][engineMessage]
      - in: query
        name: job[data][engineVersion]
      - in: query
        name: job[data][entryIds]
        description: Comma separated list of entry ids
      - in: query
        name: job[data][entryId]
        description: Live stream entry id
      - in: query
        name: job[data][eventsType]
        description: 'Enum Type: `KalturaScheduleEventType`The type of the events
          that ill be created by this upload'
      - in: query
        name: job[data][extractId3Tags]
      - in: query
        name: job[data][extraDestFileSyncs]
      - in: query
        name: job[data][fileIndex]
        description: The index of the file within the entry
      - in: query
        name: job[data][fileLocation]
      - in: query
        name: job[data][fileName]
        description: Friendly name of the file, used to be recognized later in the
          logs
      - in: query
        name: job[data][fileSize]
      - in: query
        name: job[data][filesPermissionInS3]
        description: 'Enum Type: `KalturaAmazonS3StorageProfileFilesPermissionLevel`'
      - in: query
        name: job[data][filter][advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: job[data][filter][advancedSearch][categoriesMatchOr]
      - in: query
        name: job[data][filter][advancedSearch][categoryEntryStatusIn]
      - in: query
        name: job[data][filter][advancedSearch][categoryIdEqual]
      - in: query
        name: job[data][filter][advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: job[data][filter][advancedSearch][contentLike]
      - in: query
        name: job[data][filter][advancedSearch][contentMultiLikeAnd]
      - in: query
        name: job[data][filter][advancedSearch][contentMultiLikeOr]
      - in: query
        name: job[data][filter][advancedSearch][cuePointsFreeText]
      - in: query
        name: job[data][filter][advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: job[data][filter][advancedSearch][cuePointTypeIn]
      - in: query
        name: job[data][filter][advancedSearch][depthGreaterThanEqual]
      - in: query
        name: job[data][filter][advancedSearch][distributionProfileId]
      - in: query
        name: job[data][filter][advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: job[data][filter][advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: job[data][filter][advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: job[data][filter][advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: job[data][filter][advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: job[data][filter][advancedSearch][extendedStatusIn]
      - in: query
        name: job[data][filter][advancedSearch][field]
      - in: query
        name: job[data][filter][advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: job[data][filter][advancedSearch][idEqual]
      - in: query
        name: job[data][filter][advancedSearch][idIn]
      - in: query
        name: job[data][filter][advancedSearch][indexIdGreaterThan]
      - in: query
        name: job[data][filter][advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: job[data][filter][advancedSearch][items]
      - in: query
        name: job[data][filter][advancedSearch][memberIdEq]
      - in: query
        name: job[data][filter][advancedSearch][memberIdIn]
      - in: query
        name: job[data][filter][advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: job[data][filter][advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: job[data][filter][advancedSearch][metadataProfileId]
      - in: query
        name: job[data][filter][advancedSearch][noDistributionProfiles]
      - in: query
        name: job[data][filter][advancedSearch][not]
      - in: query
        name: job[data][filter][advancedSearch][objectType]
      - in: query
        name: job[data][filter][advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: job[data][filter][advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: job[data][filter][advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: job[data][filter][advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: job[data][filter][advancedSearch][userIdEqual]
      - in: query
        name: job[data][filter][advancedSearch][userIdIn]
      - in: query
        name: job[data][filter][advancedSearch][value]
      - in: query
        name: job[data][filter][advancedSearch][watermarkId]
      - in: query
        name: job[data][filter][orderBy]
      - in: query
        name: job[data][flavorAssetId]
        description: Flavor asset to be ingested with the output
      - in: query
        name: job[data][flavorParamsId]
        description: Flavor params id to use for conversion
      - in: query
        name: job[data][flavorParamsOutputId]
      - in: query
        name: job[data][flavorParamsOutput][anamorphicPixels]
      - in: query
        name: job[data][flavorParamsOutput][aspectRatioProcessingMode]
      - in: query
        name: job[data][flavorParamsOutput][audioBitrate]
        description: The audio bitrate (in KBits) of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][audioChannels]
        description: The number of audio channels for downmixing
      - in: query
        name: job[data][flavorParamsOutput][audioCodec]
        description: 'Enum Type: `KalturaAudioCodec`The audio codec of the Flavor
          Params'
      - in: query
        name: job[data][flavorParamsOutput][audioSampleRate]
        description: The audio sample rate of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][clipDuration]
      - in: query
        name: job[data][flavorParamsOutput][clipOffset]
      - in: query
        name: job[data][flavorParamsOutput][commandLinesStr]
      - in: query
        name: job[data][flavorParamsOutput][contentAwareness]
      - in: query
        name: job[data][flavorParamsOutput][conversionEnginesExtraParams]
        description: The list of conversion engines extra params (separated with |)
      - in: query
        name: job[data][flavorParamsOutput][conversionEngines]
        description: The list of conversion engines (comma separated)
      - in: query
        name: job[data][flavorParamsOutput][deinterlice]
      - in: query
        name: job[data][flavorParamsOutput][densityHeight]
      - in: query
        name: job[data][flavorParamsOutput][densityWidth]
      - in: query
        name: job[data][flavorParamsOutput][depth]
      - in: query
        name: job[data][flavorParamsOutput][description]
        description: The description of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][engineVersion]
      - in: query
        name: job[data][flavorParamsOutput][flashVersion]
      - in: query
        name: job[data][flavorParamsOutput][flavorAssetId]
      - in: query
        name: job[data][flavorParamsOutput][flavorAssetVersion]
      - in: query
        name: job[data][flavorParamsOutput][flavorParamsId]
      - in: query
        name: job[data][flavorParamsOutput][flavorParamsVersion]
      - in: query
        name: job[data][flavorParamsOutput][forcedKeyFramesMode]
      - in: query
        name: job[data][flavorParamsOutput][forceFrameToMultiplication16]
      - in: query
        name: job[data][flavorParamsOutput][format]
        description: 'Enum Type: `KalturaContainerFormat`The container format of the
          Flavor Params'
      - in: query
        name: job[data][flavorParamsOutput][frameRate]
        description: The frame rate of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][gopSize]
        description: The gop size of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][height]
        description: The desired height of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][isAvoidForcedKeyFrames]
      - in: query
        name: job[data][flavorParamsOutput][isAvoidVideoShrinkBitrateToSource]
      - in: query
        name: job[data][flavorParamsOutput][isAvoidVideoShrinkFramesizeToSource]
      - in: query
        name: job[data][flavorParamsOutput][isCropIMX]
      - in: query
        name: job[data][flavorParamsOutput][isEncrypted]
      - in: query
        name: job[data][flavorParamsOutput][isGopInSec]
      - in: query
        name: job[data][flavorParamsOutput][isVideoFrameRateForLowBrAppleHls]
      - in: query
        name: job[data][flavorParamsOutput][maxFrameRate]
      - in: query
        name: job[data][flavorParamsOutput][mediaParserType]
        description: 'Enum Type: `KalturaMediaParserType`Media parser type to be used
          for post-conversion validation'
      - in: query
        name: job[data][flavorParamsOutput][multiStream]
      - in: query
        name: job[data][flavorParamsOutput][name]
        description: The name of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][objectType]
      - in: query
        name: job[data][flavorParamsOutput][operators]
      - in: query
        name: job[data][flavorParamsOutput][optimizationPolicy]
      - in: query
        name: job[data][flavorParamsOutput][partnerId]
      - in: query
        name: job[data][flavorParamsOutput][poly2Bitmap]
      - in: query
        name: job[data][flavorParamsOutput][readonly]
      - in: query
        name: job[data][flavorParamsOutput][readyBehavior]
      - in: query
        name: job[data][flavorParamsOutput][remoteStorageProfileIds]
        description: Comma seperated ids of remote storage profiles that the flavor
          distributed to, the distribution done by the conversion engine
      - in: query
        name: job[data][flavorParamsOutput][requiredPermissions]
      - in: query
        name: job[data][flavorParamsOutput][rotate]
      - in: query
        name: job[data][flavorParamsOutput][sizeHeight]
      - in: query
        name: job[data][flavorParamsOutput][sizeWidth]
      - in: query
        name: job[data][flavorParamsOutput][sourceAssetParamsIds]
        description: Comma seperated ids of source flavor params this flavor is created
          from
      - in: query
        name: job[data][flavorParamsOutput][sourceRemoteStorageProfileId]
        description: Id of remote storage profile that used to get the source, zero
          indicates Kaltura data center
      - in: query
        name: job[data][flavorParamsOutput][subtitlesData]
      - in: query
        name: job[data][flavorParamsOutput][systemName]
        description: System name of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][tags]
        description: The Flavor Params tags are used to identify the flavor for different
          usage (e
      - in: query
        name: job[data][flavorParamsOutput][twoPass]
      - in: query
        name: job[data][flavorParamsOutput][videoBitrateTolerance]
      - in: query
        name: job[data][flavorParamsOutput][videoBitrate]
        description: The video bitrate (in KBits) of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][videoCodec]
        description: 'Enum Type: `KalturaVideoCodec`The video codec of the Flavor
          Params'
      - in: query
        name: job[data][flavorParamsOutput][videoConstantBitrate]
      - in: query
        name: job[data][flavorParamsOutput][watermarkData]
      - in: query
        name: job[data][flavorParamsOutput][widevineDistributionEndDate]
        description: License distribution window end date
      - in: query
        name: job[data][flavorParamsOutput][widevineDistributionStartDate]
        description: License distribution window start date
      - in: query
        name: job[data][flavorParamsOutput][width]
        description: The desired width of the Flavor Params
      - in: query
        name: job[data][flavors]
      - in: query
        name: job[data][force]
      - in: query
        name: job[data][fromEmail]
      - in: query
        name: job[data][fromName]
      - in: query
        name: job[data][fromPartnerId]
        description: Id of the partner to copy from
      - in: query
        name: job[data][ftpPassiveMode]
      - in: query
        name: job[data][inputFileSyncLocalPath]
      - in: query
        name: job[data][inputXmlLocalPath]
      - in: query
        name: job[data][inputXmlRemoteUrl]
      - in: query
        name: job[data][isHtml]
      - in: query
        name: job[data][keepDistributionItem]
        description: Flag signifying that the associated distribution item should
          not be moved to removed status
      - in: query
        name: job[data][ksType]
        description: 'Enum Type: `KalturaSessionType`'
      - in: query
        name: job[data][language]
        description: 'Enum Type: `KalturaLanguageCode`'
      - in: query
        name: job[data][lastCuePointSyncTime]
        description: last live to vod sync time
      - in: query
        name: job[data][lastMovedCategoryEntryPageIndex]
        description: Saves the last page index of the category entries filter pager     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastMovedCategoryId]
        description: Saves the last category id that its entries moved completely     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastMovedCategoryPageIndex]
        description: Saves the last page index of the child categories filter pager     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastSegmentDrift]
        description: last segment drift
      - in: query
        name: job[data][lastSegmentDuration]
        description: last Segment Duration
      - in: query
        name: job[data][lastUpdatedCategoryCreatedAt]
        description: Saves the last sub category creation date that was updated     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastUpdatedCategoryEntryCreatedAt]
        description: Saves the last category entry creation date that was updated     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][liveEntryId]
        description: live Entry Id
      - in: query
        name: job[data][localFileSyncPath]
      - in: query
        name: job[data][logFileSyncLocalPath]
      - in: query
        name: job[data][logFileSyncRemoteUrl]
      - in: query
        name: job[data][mailPriority]
      - in: query
        name: job[data][mailType]
        description: 'Enum Type: `KalturaMailType`'
      - in: query
        name: job[data][maxResults]
      - in: query
        name: job[data][mediaServerIndex]
        description: 'Enum Type: `KalturaEntryServerNodeType`Primary or secondary
          media server'
      - in: query
        name: job[data][mediaType]
      - in: query
        name: job[data][metadataId]
      - in: query
        name: job[data][metadataProfileId]
      - in: query
        name: job[data][method]
        description: 'Enum Type: `KalturaHttpNotificationMethod`Request method'
      - in: query
        name: job[data][minSendDate]
      - in: query
        name: job[data][modifiedAttributes]
      - in: query
        name: job[data][monitorSyncCompletion]
      - in: query
        name: job[data][moveFromChildren]
        description: All entries from all child categories will be moved as well
      - in: query
        name: job[data][multiLanaguageCaptionAssetId]
      - in: query
        name: job[data][notificationEmail]
      - in: query
        name: job[data][notificationResult]
      - in: query
        name: job[data][numberOfAttempts]
      - in: query
        name: job[data][objectData][conversionProfileId]
        description: Selected profile id for all bulk entries
      - in: query
        name: job[data][objectData][objectType]
      - in: query
        name: job[data][objectId]
      - in: query
        name: job[data][objectType]
      - in: query
        name: job[data][objType]
        description: 'Enum Type: `KalturaNotificationObjectType`'
      - in: query
        name: job[data][offset]
        description: Clipping offset in seconds
      - in: query
        name: job[data][outputPath]
      - in: query
        name: job[data][parsedSlug]
      - in: query
        name: job[data][parsedUserId]
      - in: query
        name: job[data][passPhrase]
      - in: query
        name: job[data][password]
        description: A password to use for the connection
      - in: query
        name: job[data][plays]
      - in: query
        name: job[data][primaryBroadcastingUrl]
      - in: query
        name: job[data][primaryContact]
      - in: query
        name: job[data][privateKey]
      - in: query
        name: job[data][protocol]
        description: http / https
      - in: query
        name: job[data][providerData][additionalParameters]
        description: additional parameters to send to Cielo24
      - in: query
        name: job[data][providerData][captionAssetFormats]
        description: Caption formats
      - in: query
        name: job[data][providerData][entryId]
        description: Entry ID
      - in: query
        name: job[data][providerData][exampleUrl]
        description: Just an example
      - in: query
        name: job[data][providerData][fidelity]
        description: 'Enum Type: `KalturaCielo24Fidelity`'
      - in: query
        name: job[data][providerData][flavorAssetId]
        description: Flavor ID
      - in: query
        name: job[data][providerData][metadataProfileId]
        description: ID of the metadata profile for the extracted term metadata
      - in: query
        name: job[data][providerData][objectType]
      - in: query
        name: job[data][providerData][priority]
        description: 'Enum Type: `KalturaCielo24Priority`'
      - in: query
        name: job[data][providerData][replaceMediaContent]
        description: should replace remote media content
      - in: query
        name: job[data][providerData][spokenLanguage]
        description: 'Enum Type: `KalturaLanguage`Transcript content language'
      - in: query
        name: job[data][providerData][transcriptAssetId]
        description: ID of the transcript asset
      - in: query
        name: job[data][providerData][transcriptId]
        description: input Transcript-asset ID
      - in: query
        name: job[data][providerData][voicebaseApiKey]
        description: Voicebase API key to fetch transcript tokens
      - in: query
        name: job[data][providerData][voicebaseApiPassword]
        description: Voicebase API password to fetch transcript tokens
      - in: query
        name: job[data][providerType]
        description: 'Enum Type: `KalturaIntegrationProviderType`'
      - in: query
        name: job[data][provisioningParams]
      - in: query
        name: job[data][publicKey]
      - in: query
        name: job[data][puserId]
        description: The id of the requesting user
      - in: query
        name: job[data][recipientEmail]
      - in: query
        name: job[data][recipientId]
        description: kuserId
      - in: query
        name: job[data][recipientName]
      - in: query
        name: job[data][referenceTime]
      - in: query
        name: job[data][remoteMediaId]
      - in: query
        name: job[data][resultsFilePath]
      - in: query
        name: job[data][returnVal]
      - in: query
        name: job[data][rtmp]
      - in: query
        name: job[data][s3Region]
      - in: query
        name: job[data][scanResult]
        description: 'Enum Type: `KalturaVirusScanJobResult`'
      - in: query
        name: job[data][secondaryBroadcastingUrl]
      - in: query
        name: job[data][secondaryContact]
      - in: query
        name: job[data][separator]
      - in: query
        name: job[data][serverPassPhrase]
      - in: query
        name: job[data][serverPassword]
      - in: query
        name: job[data][serverPrivateKey]
      - in: query
        name: job[data][serverPublicKey]
      - in: query
        name: job[data][serverUrl]
      - in: query
        name: job[data][serverUsername]
      - in: query
        name: job[data][server][dc]
        description: The dc of the server
      - in: query
        name: job[data][server][description]
      - in: query
        name: job[data][server][host]
      - in: query
        name: job[data][server][name]
      - in: query
        name: job[data][server][objectType]
      - in: query
        name: job[data][server][password]
      - in: query
        name: job[data][server][port]
      - in: query
        name: job[data][server][protocol]
        description: 'Enum Type: `KalturaActivitiBusinessProcessServerProtocol`'
      - in: query
        name: job[data][server][systemName]
      - in: query
        name: job[data][server][username]
      - in: query
        name: job[data][serviceToken]
      - in: query
        name: job[data][signatureType]
      - in: query
        name: job[data][signSecret]
        description: The secret to sign the notification with
      - in: query
        name: job[data][srcAssetId]
      - in: query
        name: job[data][srcAssetType]
        description: 'Enum Type: `KalturaAssetType`'
      - in: query
        name: job[data][srcCategoryId]
        description: Source category id
      - in: query
        name: job[data][srcFilePath]
        description: The recorded live media
      - in: query
        name: job[data][srcFileSyncId]
      - in: query
        name: job[data][srcFileSyncLocalPath]
      - in: query
        name: job[data][srcFileSyncRemoteUrl]
      - in: query
        name: job[data][srcFileSyncs]
      - in: query
        name: job[data][srcFiles]
      - in: query
        name: job[data][srcFileUrl]
      - in: query
        name: job[data][srcVersion]
      - in: query
        name: job[data][srcXslPath]
      - in: query
        name: job[data][sseKmsKeyId]
      - in: query
        name: job[data][sseType]
      - in: query
        name: job[data][sslCertificatePassword]
        description: The password required to use the certificate
      - in: query
        name: job[data][sslCertificateType]
        description: 'Enum Type: `KalturaHttpNotificationCertificateType`The format
          of the certificate'
      - in: query
        name: job[data][sslCertificate]
        description: SSL certificate to verify the peer with
      - in: query
        name: job[data][sslEngineDefault]
        description: The identifier for the crypto engine used for asymmetric crypto
          operations
      - in: query
        name: job[data][sslEngine]
        description: The identifier for the crypto engine of the private SSL key specified
          in ssl key
      - in: query
        name: job[data][sslKeyPassword]
        description: The secret password needed to use the private SSL key specified
          in ssl key
      - in: query
        name: job[data][sslKeyType]
        description: 'Enum Type: `KalturaHttpNotificationSslKeyType`The key type of
          the private SSL key specified in ssl key - PEM / DER / ENG'
      - in: query
        name: job[data][sslKey]
        description: Private SSL key
      - in: query
        name: job[data][sslVersion]
        description: 'Enum Type: `KalturaHttpNotificationSslVersion`The SSL version
          (2 or 3) to use'
      - in: query
        name: job[data][startObjectKey]
      - in: query
        name: job[data][status]
        description: 'Enum Type: `KalturaMailJobStatus`'
      - in: query
        name: job[data][streamID]
      - in: query
        name: job[data][streamName]
      - in: query
        name: job[data][streamType]
        description: 'Enum Type: `KalturaAkamaiUniversalStreamType`'
      - in: query
        name: job[data][subjectParams]
      - in: query
        name: job[data][syncMode]
        description: 'Enum Type: `KalturaWidevineRepositorySyncMode`'
      - in: query
        name: job[data][systemPassword]
      - in: query
        name: job[data][systemUserName]
      - in: query
        name: job[data][templateId]
      - in: query
        name: job[data][templatePath]
      - in: query
        name: job[data][thumbAssetId]
      - in: query
        name: job[data][thumbBitrate]
        description: The bit rate of last created thumbnail, will be used to comapare
          if this thumbnail is the best we can have
      - in: query
        name: job[data][thumbHeight]
        description: The height of last created thumbnail, will be used to comapare
          if this thumbnail is the best we can have
      - in: query
        name: job[data][thumbOffset]
        description: The position of the thumbnail in the media file
      - in: query
        name: job[data][thumbParamsOutputId]
      - in: query
        name: job[data][thumbPath]
      - in: query
        name: job[data][timeout]
        description: The maximum number of seconds to allow cURL functions to execute
      - in: query
        name: job[data][timeReference]
      - in: query
        name: job[data][timeZoneOffset]
      - in: query
        name: job[data][toPartnerId]
        description: Id of the partner to copy to
      - in: query
        name: job[data][totalVodDuration]
        description: total VOD Duration
      - in: query
        name: job[data][to][categoryUserFilter][categoryDirectMembers]
        description: Return the list of categoryUser that are not inherited from parent
          category - only the direct categoryUsers
      - in: query
        name: job[data][to][categoryUserFilter][categoryFullIdsEqual]
      - in: query
        name: job[data][to][categoryUserFilter][categoryFullIdsStartsWith]
      - in: query
        name: job[data][to][categoryUserFilter][categoryIdEqual]
      - in: query
        name: job[data][to][categoryUserFilter][categoryIdIn]
      - in: query
        name: job[data][to][categoryUserFilter][createdAtGreaterThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][createdAtLessThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][freeText]
        description: Free text search on user id or screen name
      - in: query
        name: job[data][to][categoryUserFilter][orderBy]
      - in: query
        name: job[data][to][categoryUserFilter][permissionLevelEqual]
        description: 'Enum Type: `KalturaCategoryUserPermissionLevel`'
      - in: query
        name: job[data][to][categoryUserFilter][permissionLevelIn]
      - in: query
        name: job[data][to][categoryUserFilter][permissionNamesMatchAnd]
      - in: query
        name: job[data][to][categoryUserFilter][permissionNamesMatchOr]
      - in: query
        name: job[data][to][categoryUserFilter][permissionNamesNotContains]
      - in: query
        name: job[data][to][categoryUserFilter][relatedGroupsByUserId]
        description: Return a list of categoryUser that related to the userId in this
          field by groups
      - in: query
        name: job[data][to][categoryUserFilter][statusEqual]
        description: 'Enum Type: `KalturaCategoryUserStatus`'
      - in: query
        name: job[data][to][categoryUserFilter][statusIn]
      - in: query
        name: job[data][to][categoryUserFilter][updatedAtGreaterThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][updatedAtLessThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][updateMethodEqual]
        description: 'Enum Type: `KalturaUpdateMethodType`'
      - in: query
        name: job[data][to][categoryUserFilter][updateMethodIn]
      - in: query
        name: job[data][to][categoryUserFilter][userIdEqual]
      - in: query
        name: job[data][to][categoryUserFilter][userIdIn]
      - in: query
        name: job[data][to][emailRecipients]
      - in: query
        name: job[data][to][filter][createdAtGreaterThanOrEqual]
      - in: query
        name: job[data][to][filter][createdAtLessThanOrEqual]
      - in: query
        name: job[data][to][filter][emailLike]
      - in: query
        name: job[data][to][filter][emailStartsWith]
      - in: query
        name: job[data][to][filter][firstNameOrLastNameStartsWith]
      - in: query
        name: job[data][to][filter][firstNameStartsWith]
      - in: query
        name: job[data][to][filter][idEqual]
      - in: query
        name: job[data][to][filter][idIn]
      - in: query
        name: job[data][to][filter][idOrScreenNameStartsWith]
      - in: query
        name: job[data][to][filter][isAdminEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: job[data][to][filter][lastNameStartsWith]
      - in: query
        name: job[data][to][filter][loginEnabledEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: job[data][to][filter][objectType]
      - in: query
        name: job[data][to][filter][orderBy]
      - in: query
        name: job[data][to][filter][partnerIdEqual]
      - in: query
        name: job[data][to][filter][permissionNamesMultiLikeAnd]
        description: Permission names filter expression
      - in: query
        name: job[data][to][filter][permissionNamesMultiLikeOr]
        description: Permission names filter expression
      - in: query
        name: job[data][to][filter][roleIdEqual]
      - in: query
        name: job[data][to][filter][roleIdsEqual]
      - in: query
        name: job[data][to][filter][roleIdsIn]
      - in: query
        name: job[data][to][filter][screenNameLike]
      - in: query
        name: job[data][to][filter][screenNameStartsWith]
      - in: query
        name: job[data][to][filter][statusEqual]
        description: 'Enum Type: `KalturaUserStatus`'
      - in: query
        name: job[data][to][filter][statusIn]
      - in: query
        name: job[data][to][filter][tagsMultiLikeAnd]
      - in: query
        name: job[data][to][filter][tagsMultiLikeOr]
      - in: query
        name: job[data][to][filter][typeEqual]
        description: 'Enum Type: `KalturaUserType`'
      - in: query
        name: job[data][to][filter][typeIn]
      - in: query
        name: job[data][to][objectType]
      - in: query
        name: job[data][typeAsString]
      - in: query
        name: job[data][type]
        description: 'Enum Type: `KalturaNotificationType`'
      - in: query
        name: job[data][url]
        description: Remote server URL
      - in: query
        name: job[data][userId]
      - in: query
        name: job[data][username]
        description: A username to use for the connection
      - in: query
        name: job[data][userRoles]
      - in: query
        name: job[data][views]
      - in: query
        name: job[data][virusFoundAction]
        description: 'Enum Type: `KalturaVirusFoundAction`'
      - in: query
        name: job[data][vodEntryId]
        description: $vod Entry Id
      - in: query
        name: job[data][webexHostId]
      - in: query
        name: job[data][wsdlPassword]
      - in: query
        name: job[data][wsdlUsername]
      - in: query
        name: job[data][wvAssetIds]
      - in: query
        name: job[entryId]
      - in: query
        name: job[entryName]
      - in: query
        name: job[jobSubType]
      - in: query
        name: lockKey[batchIndex]
      - in: query
        name: lockKey[schedulerId]
      - in: query
        name: lockKey[workerId]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - UpdateExclusiveConvertCollectionJob
  /service/batch/action/updateExclusiveJob:
    get:
      summary: Get Service Batch Action Updateexclusivejob
      description: batch updateExclusiveJobAction action updates a BatchJob of extended
        type that was claimed using the getExclusiveJobs
      operationId: batch.updateExclusiveJob
      x-api-path-slug: servicebatchactionupdateexclusivejob-get
      parameters:
      - in: query
        name: id
        description: The id of the job to free
      - in: query
        name: job[data][actualSrcFileSyncLocalPath]
        description: The translated path as used by the scheduler
      - in: query
        name: job[data][addedPrivacyContexts]
      - in: query
        name: job[data][amfArray]
        description: amf Array File Path
      - in: query
        name: job[data][assetId]
      - in: query
        name: job[data][authenticationMethod]
        description: 'Enum Type: `KalturaHttpNotificationAuthenticationMethod`The
          HTTP authentication method to use'
      - in: query
        name: job[data][backupEncoderIP]
      - in: query
        name: job[data][backupStreamID]
      - in: query
        name: job[data][bodyParams]
      - in: query
        name: job[data][cachedObjectType]
        description: Class name
      - in: query
        name: job[data][calculateComplexity]
      - in: query
        name: job[data][campaignId]
      - in: query
        name: job[data][captionAssetId]
      - in: query
        name: job[data][categoryId]
        description: category id
      - in: query
        name: job[data][changedCategoryId]
      - in: query
        name: job[data][columns]
      - in: query
        name: job[data][commandLinesStr]
      - in: query
        name: job[data][concatenatedDuration]
        description: duration of the concated video
      - in: query
        name: job[data][connectTimeout]
        description: The number of seconds to wait while trying to connect
      - in: query
        name: job[data][contentMatchPolicy]
        description: 'Enum Type: `KalturaDropFolderContentFileHandlerMatchPolicy`'
      - in: query
        name: job[data][contentMoid]
        description: Unique Kontiki MOID for the content uploaded to Kontiki
      - in: query
        name: job[data][contentParameters]
      - in: query
        name: job[data][conversionProfileId]
      - in: query
        name: job[data][cpcode]
      - in: query
        name: job[data][createLink]
      - in: query
        name: job[data][createThumb]
        description: Indicates if a thumbnail should be created
      - in: query
        name: job[data][customData]
      - in: query
        name: job[data][customHeaders]
      - in: query
        name: job[data][data]
      - in: query
        name: job[data][deletedPrivacyContexts]
      - in: query
        name: job[data][description]
      - in: query
        name: job[data][destCategoryFullIds]
        description: Destination categories fallback ids
      - in: query
        name: job[data][destCategoryId]
        description: Destination category id
      - in: query
        name: job[data][destDataFilePath]
        description: The data output file
      - in: query
        name: job[data][destDirLocalPath]
      - in: query
        name: job[data][destDirRemoteUrl]
      - in: query
        name: job[data][destFileLocalPath]
      - in: query
        name: job[data][destFileName]
      - in: query
        name: job[data][destFilePath]
        description: Output file
      - in: query
        name: job[data][destFileSyncLocalPath]
      - in: query
        name: job[data][destFileSyncRemoteUrl]
      - in: query
        name: job[data][destFileSyncStoredPath]
      - in: query
        name: job[data][destVersion]
      - in: query
        name: job[data][destXsdPath]
      - in: query
        name: job[data][detectGOP]
      - in: query
        name: job[data][distributionProfileId]
      - in: query
        name: job[data][distributionProfile][accountId]
      - in: query
        name: job[data][distributionProfile][adFreeApplicationGuid]
        description: The GUID for the application in which to record metrics and enforce
          business rules obtained through your Unicorn representative
      - in: query
        name: job[data][distributionProfile][adServerPartnerId]
      - in: query
        name: job[data][distributionProfile][allowAdsenseForVideo]
      - in: query
        name: job[data][distributionProfile][allowComments]
      - in: query
        name: job[data][distributionProfile][allowDownload]
      - in: query
        name: job[data][distributionProfile][allowEmbedding]
      - in: query
        name: job[data][distributionProfile][allowInvideo]
      - in: query
        name: job[data][distributionProfile][allowMidRollAds]
      - in: query
        name: job[data][distributionProfile][allowPostRollAds]
      - in: query
        name: job[data][distributionProfile][allowPreRollAds]
      - in: query
        name: job[data][distributionProfile][allowRatings]
      - in: query
        name: job[data][distributionProfile][allowResponses]
      - in: query
        name: job[data][distributionProfile][allowStreaming]
      - in: query
        name: job[data][distributionProfile][allowSyndication]
      - in: query
        name: job[data][distributionProfile][apiAuthorizeUrl]
      - in: query
        name: job[data][distributionProfile][apiHostUrl]
        description: The API host URL that the Upload User should have access to,
          Used for HTTP content submission
      - in: query
        name: job[data][distributionProfile][apikey]
      - in: query
        name: job[data][distributionProfile][asperaHost]
      - in: query
        name: job[data][distributionProfile][asperaLogin]
      - in: query
        name: job[data][distributionProfile][asperaPass]
      - in: query
        name: job[data][distributionProfile][asperaPrivateKey]
      - in: query
        name: job[data][distributionProfile][asperaPublicKey]
      - in: query
        name: job[data][distributionProfile][assetFilenameXslt]
      - in: query
        name: job[data][distributionProfile][assumeSuccess]
      - in: query
        name: job[data][distributionProfile][autoCreateFlavors]
        description: Comma separated flavor params ids that should be auto converted
      - in: query
        name: job[data][distributionProfile][autoCreateThumb]
        description: Comma separated thumbnail params ids that should be auto generated
      - in: query
        name: job[data][distributionProfile][backgroundImageStandard]
      - in: query
        name: job[data][distributionProfile][backgroundImageWide]
      - in: query
        name: job[data][distributionProfile][basePath]
      - in: query
        name: job[data][distributionProfile][blockOutsideOwnership]
      - in: query
        name: job[data][distributionProfile][bodyXslt]
      - in: query
        name: job[data][distributionProfile][captionAutosync]
      - in: query
        name: job[data][distributionProfile][categoryId]
      - in: query
        name: job[data][distributionProfile][certificateKey]
      - in: query
        name: job[data][distributionProfile][channelCopyright]
      - in: query
        name: job[data][distributionProfile][channelDescription]
      - in: query
        name: job[data][distributionProfile][channelGenerator]
      - in: query
        name: job[data][distributionProfile][channelGuid]
        description: The Channel GUID assigned to this Publication Rule
      - in: query
        name: job[data][distributionProfile][channelImageHeight]
      - in: query
        name: job[data][distributionProfile][channelImageLink]
      - in: query
        name: job[data][distributionProfile][channelImageTitle]
      - in: query
        name: job[data][distributionProfile][channelImageUrl]
      - in: query
        name: job[data][distributionProfile][channelImageWidth]
      - in: query
        name: job[data][distributionProfile][channelLanguage]
      - in: query
        name: job[data][distributionProfile][channelLink]
      - in: query
        name: job[data][distributionProfile][channelManagingEditor]
      - in: query
        name: job[data][distributionProfile][channelRating]
      - in: query
        name: job[data][distributionProfile][channelTitle]
      - in: query
        name: job[data][distributionProfile][claimType]
      - in: query
        name: job[data][distributionProfile][commercialPolicy]
      - in: query
        name: job[data][distributionProfile][contactEmail]
      - in: query
        name: job[data][distributionProfile][contactTelephone]
      - in: query
        name: job[data][distributionProfile][contentOwner]
      - in: query
        name: job[data][distributionProfile][copyright]
      - in: query
        name: job[data][distributionProfile][cPlatformTvSeriesField]
      - in: query
        name: job[data][distributionProfile][cPlatformTvSeries]
      - in: query
        name: job[data][distributionProfile][csId]
      - in: query
        name: job[data][distributionProfile][cuePointsProvider]
      - in: query
        name: job[data][distributionProfile][defaultCategory]
      - in: query
        name: job[data][distributionProfile][deleteEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][deleteReference]
      - in: query
        name: job[data][distributionProfile][disableEpisodeNumberCustomValidation]
      - in: query
        name: job[data][distributionProfile][disableMetadata]
      - in: query
        name: job[data][distributionProfile][distributeCaptions]
      - in: query
        name: job[data][distributionProfile][distributeCuePoints]
      - in: query
        name: job[data][distributionProfile][distributeRemoteCaptionAssetContent]
      - in: query
        name: job[data][distributionProfile][distributeRemoteFlavorAssetContent]
      - in: query
        name: job[data][distributionProfile][distributeRemoteThumbAssetContent]
      - in: query
        name: job[data][distributionProfile][domainGuid]
        description: The GUID of the Customer Domain in the Unicorn system obtained
          by contacting your Unicorn representative
      - in: query
        name: job[data][distributionProfile][domainName]
        description: The name of the Domain that the Upload User should have access
          to, Used for authentication
      - in: query
        name: job[data][distributionProfile][domain]
      - in: query
        name: job[data][distributionProfile][downloadPriceCode]
      - in: query
        name: job[data][distributionProfile][email]
      - in: query
        name: job[data][distributionProfile][enableAdServer]
      - in: query
        name: job[data][distributionProfile][entitlements]
      - in: query
        name: job[data][distributionProfile][entitlement]
      - in: query
        name: job[data][distributionProfile][feedAuthorName]
      - in: query
        name: job[data][distributionProfile][feedCopyright]
      - in: query
        name: job[data][distributionProfile][feedDescription]
      - in: query
        name: job[data][distributionProfile][feedImageHeight]
      - in: query
        name: job[data][distributionProfile][feedImageLink]
      - in: query
        name: job[data][distributionProfile][feedImageTitle]
      - in: query
        name: job[data][distributionProfile][feedImageUrl]
      - in: query
        name: job[data][distributionProfile][feedImageWidth]
      - in: query
        name: job[data][distributionProfile][feedLanguage]
      - in: query
        name: job[data][distributionProfile][feedLastBuildDate]
      - in: query
        name: job[data][distributionProfile][feedLink]
      - in: query
        name: job[data][distributionProfile][feedSpecVersion]
        description: 'Enum Type: `KalturaYouTubeDistributionFeedSpecVersion`'
      - in: query
        name: job[data][distributionProfile][feedSubtitle]
      - in: query
        name: job[data][distributionProfile][feedTitle]
      - in: query
        name: job[data][distributionProfile][fieldConfigArray]
      - in: query
        name: job[data][distributionProfile][flavorAssetFilenameXslt]
      - in: query
        name: job[data][distributionProfile][flvFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][ftpHost]
      - in: query
        name: job[data][distributionProfile][ftpLogin]
      - in: query
        name: job[data][distributionProfile][ftpPassword]
      - in: query
        name: job[data][distributionProfile][ftpPass]
      - in: query
        name: job[data][distributionProfile][ftpPath]
      - in: query
        name: job[data][distributionProfile][ftpUsername]
      - in: query
        name: job[data][distributionProfile][genericProviderId]
        description: '`insertOnly`'
      - in: query
        name: job[data][distributionProfile][geoBlockingMapping]
        description: 'Enum Type: `KalturaDailymotionGeoBlockingMapping`'
      - in: query
        name: job[data][distributionProfile][googleClientId]
      - in: query
        name: job[data][distributionProfile][googleClientSecret]
      - in: query
        name: job[data][distributionProfile][googleTokenData]
      - in: query
        name: job[data][distributionProfile][hideViewCount]
      - in: query
        name: job[data][distributionProfile][host]
      - in: query
        name: job[data][distributionProfile][ignoreSchedulingInFeed]
      - in: query
        name: job[data][distributionProfile][ingestUrl]
      - in: query
        name: job[data][distributionProfile][instreamStandard]
      - in: query
        name: job[data][distributionProfile][instreamTrueview]
      - in: query
        name: job[data][distributionProfile][ips]
      - in: query
        name: job[data][distributionProfile][itemLink]
      - in: query
        name: job[data][distributionProfile][itemMediaRating]
      - in: query
        name: job[data][distributionProfile][itemsPerPage]
      - in: query
        name: job[data][distributionProfile][itemType]
      - in: query
        name: job[data][distributionProfile][itemXpathsToExtend]
      - in: query
        name: job[data][distributionProfile][mapAccessControlProfileIds]
      - in: query
        name: job[data][distributionProfile][mapCaptionParamsIds]
      - in: query
        name: job[data][distributionProfile][mapConversionProfileIds]
      - in: query
        name: job[data][distributionProfile][mapFlavorParamsIds]
      - in: query
        name: job[data][distributionProfile][mapMetadataProfileIds]
      - in: query
        name: job[data][distributionProfile][mapStorageProfileIds]
      - in: query
        name: job[data][distributionProfile][mapThumbParamsIds]
      - in: query
        name: job[data][distributionProfile][metadataFilenameXslt]
      - in: query
        name: job[data][distributionProfile][metadataProfileId]
      - in: query
        name: job[data][distributionProfile][metadataXpathsTriggerUpdate]
      - in: query
        name: job[data][distributionProfile][metadataXslt]
      - in: query
        name: job[data][distributionProfile][msnvideoCat]
      - in: query
        name: job[data][distributionProfile][msnvideoTopCat]
      - in: query
        name: job[data][distributionProfile][msnvideoTop]
      - in: query
        name: job[data][distributionProfile][name]
      - in: query
        name: job[data][distributionProfile][notificationEmail]
      - in: query
        name: job[data][distributionProfile][objectType]
      - in: query
        name: job[data][distributionProfile][optionalAssetDistributionRules]
      - in: query
        name: job[data][distributionProfile][optionalFlavorParamsIds]
        description: Comma separated flavor params ids that should be submitted if
          ready
      - in: query
        name: job[data][distributionProfile][optionalThumbDimensions]
      - in: query
        name: job[data][distributionProfile][overrideManualEdits]
      - in: query
        name: job[data][distributionProfile][ownerName]
      - in: query
        name: job[data][distributionProfile][pageAccessToken]
      - in: query
        name: job[data][distributionProfile][pageGroup]
      - in: query
        name: job[data][distributionProfile][pageId]
      - in: query
        name: job[data][distributionProfile][passphrase]
      - in: query
        name: job[data][distributionProfile][password]
      - in: query
        name: job[data][distributionProfile][permissions]
      - in: query
        name: job[data][distributionProfile][port]
      - in: query
        name: job[data][distributionProfile][priority]
      - in: query
        name: job[data][distributionProfile][privacyStatus]
      - in: query
        name: job[data][distributionProfile][processFeed]
        description: 'Enum Type: `KalturaYahooDistributionProcessFeedActionStatus`'
      - in: query
        name: job[data][distributionProfile][protocol]
        description: '`insertOnly`Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: job[data][distributionProfile][providerId]
      - in: query
        name: job[data][distributionProfile][providerName]
      - in: query
        name: job[data][distributionProfile][providerType]
        description: '`insertOnly`Enum Type: `KalturaDistributionProviderType`'
      - in: query
        name: job[data][distributionProfile][rating]
      - in: query
        name: job[data][distributionProfile][recommendedDcForDownload]
        description: The best Kaltura data center to be used to download the asset
          files to
      - in: query
        name: job[data][distributionProfile][recommendedDcForExecute]
        description: The best Kaltura data center to be used to execute the distribution
          job
      - in: query
        name: job[data][distributionProfile][recommendedStorageProfileForDownload]
        description: The best external storage to be used to download the asset files
          from
      - in: query
        name: job[data][distributionProfile][releaseClaims]
      - in: query
        name: job[data][distributionProfile][remoteAssetParamsId]
        description: The flavor-params that will be used for the remote asset
      - in: query
        name: job[data][distributionProfile][replaceAirDates]
      - in: query
        name: job[data][distributionProfile][replaceGroup]
      - in: query
        name: job[data][distributionProfile][reportEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][requiredAssetDistributionRules]
      - in: query
        name: job[data][distributionProfile][requiredFlavorParamsIds]
        description: Comma separated flavor params ids that required to be ready before
          submission
      - in: query
        name: job[data][distributionProfile][requiredThumbDimensions]
      - in: query
        name: job[data][distributionProfile][reRequestPermissions]
      - in: query
        name: job[data][distributionProfile][seasonNumber]
      - in: query
        name: job[data][distributionProfile][seasonSynopsis]
      - in: query
        name: job[data][distributionProfile][seasonTuneInInformation]
      - in: query
        name: job[data][distributionProfile][sendMetadataAfterAssets]
      - in: query
        name: job[data][distributionProfile][seriesAdditionalCategories]
      - in: query
        name: job[data][distributionProfile][seriesChannel]
      - in: query
        name: job[data][distributionProfile][seriesPrimaryCategory]
      - in: query
        name: job[data][distributionProfile][sftpBaseDir]
      - in: query
        name: job[data][distributionProfile][sftpBasePath]
      - in: query
        name: job[data][distributionProfile][sftpHost]
      - in: query
        name: job[data][distributionProfile][sftpLogin]
      - in: query
        name: job[data][distributionProfile][sftpPass]
      - in: query
        name: job[data][distributionProfile][sftpPort]
      - in: query
        name: job[data][distributionProfile][sftpPrivateKey]
      - in: query
        name: job[data][distributionProfile][sftpPublicKey]
      - in: query
        name: job[data][distributionProfile][shouldAddThumbExtension]
      - in: query
        name: job[data][distributionProfile][shouldIncludeCaptions]
      - in: query
        name: job[data][distributionProfile][shouldIncludeCuePoints]
      - in: query
        name: job[data][distributionProfile][slFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][slHdFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][sourceFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][sourceFriendlyName]
      - in: query
        name: job[data][distributionProfile][source]
      - in: query
        name: job[data][distributionProfile][state]
      - in: query
        name: job[data][distributionProfile][status]
        description: 'Enum Type: `KalturaDistributionProfileStatus`'
      - in: query
        name: job[data][distributionProfile][storageProfileId]
        description: The remote storage that should be used for the remote asset
      - in: query
        name: job[data][distributionProfile][streamingPriceCode]
      - in: query
        name: job[data][distributionProfile][strict]
      - in: query
        name: job[data][distributionProfile][submitAction][ftpPassiveMode]
      - in: query
        name: job[data][distributionProfile][submitAction][httpFieldName]
      - in: query
        name: job[data][distributionProfile][submitAction][httpFileName]
      - in: query
        name: job[data][distributionProfile][submitAction][password]
      - in: query
        name: job[data][distributionProfile][submitAction][protocol]
        description: 'Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: job[data][distributionProfile][submitAction][serverPath]
      - in: query
        name: job[data][distributionProfile][submitAction][serverUrl]
      - in: query
        name: job[data][distributionProfile][submitAction][username]
      - in: query
        name: job[data][distributionProfile][submitEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][sunriseDefaultOffset]
        description: If entry distribution sunrise not specified that will be the
          default since entry creation time, in seconds
      - in: query
        name: job[data][distributionProfile][sunsetDefaultOffset]
        description: If entry distribution sunset not specified that will be the default
          since entry creation time, in seconds
      - in: query
        name: job[data][distributionProfile][tags]
      - in: query
        name: job[data][distributionProfile][targetAccountId]
      - in: query
        name: job[data][distributionProfile][targetLoginId]
      - in: query
        name: job[data][distributionProfile][targetLoginPassword]
      - in: query
        name: job[data][distributionProfile][targetServiceUrl]
      - in: query
        name: job[data][distributionProfile][target]
      - in: query
        name: job[data][distributionProfile][thumbnailAssetFilenameXslt]
      - in: query
        name: job[data][distributionProfile][ugcPolicy]
      - in: query
        name: job[data][distributionProfile][updateEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: job[data][distributionProfile][upstreamNetworkId]
      - in: query
        name: job[data][distributionProfile][upstreamNetworkName]
      - in: query
        name: job[data][distributionProfile][upstreamVideoId]
      - in: query
        name: job[data][distributionProfile][urgentReference]
      - in: query
        name: job[data][distributionProfile][useCategoryEntries]
        description: When checking custom XSLT conditions using the fieldConfigArray
          - address only categories associated with the entry via the categoryEntry
          object
      - in: query
        name: job[data][distributionProfile][userAccessToken]
      - in: query
        name: job[data][distributionProfile][username]
      - in: query
        name: job[data][distributionProfile][user]
      - in: query
        name: job[data][distributionProfile][videoMediaType]
      - in: query
        name: job[data][distributionProfile][wmvFlavorParamsId]
      - in: query
        name: job[data][distributionProfile][xsltFile]
      - in: query
        name: job[data][distributionProfile][xsl]
      - in: query
        name: job[data][domainName]
      - in: query
        name: job[data][dropFolderFileIds]
      - in: query
        name: job[data][dropFolderFileId]
      - in: query
        name: job[data][dropFolderId]
      - in: query
        name: job[data][duration]
        description: Clipping duration in seconds
      - in: query
        name: job[data][dvrEnabled]
        description: 'Enum Type: `KalturaDVRStatus`'
      - in: query
        name: job[data][dvrWindow]
      - in: query
        name: job[data][emailId]
      - in: query
        name: job[data][encoderIP]
      - in: query
        name: job[data][encoderPassword]
      - in: query
        name: job[data][encoderUsername]
      - in: query
        name: job[data][endDate]
      - in: query
        name: job[data][endObjectKey]
      - in: query
        name: job[data][endPoint]
      - in: query
        name: job[data][endTime]
        description: Duration of the live entry including all recorded segments including
          the current
      - in: query
        name: job[data][engineMessage]
      - in: query
        name: job[data][engineVersion]
      - in: query
        name: job[data][entryIds]
        description: Comma separated list of entry ids
      - in: query
        name: job[data][entryId]
        description: Live stream entry id
      - in: query
        name: job[data][eventsType]
        description: 'Enum Type: `KalturaScheduleEventType`The type of the events
          that ill be created by this upload'
      - in: query
        name: job[data][extractId3Tags]
      - in: query
        name: job[data][extraDestFileSyncs]
      - in: query
        name: job[data][fileIndex]
        description: The index of the file within the entry
      - in: query
        name: job[data][fileLocation]
      - in: query
        name: job[data][fileName]
        description: Friendly name of the file, used to be recognized later in the
          logs
      - in: query
        name: job[data][fileSize]
      - in: query
        name: job[data][filesPermissionInS3]
        description: 'Enum Type: `KalturaAmazonS3StorageProfileFilesPermissionLevel`'
      - in: query
        name: job[data][filter][advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: job[data][filter][advancedSearch][categoriesMatchOr]
      - in: query
        name: job[data][filter][advancedSearch][categoryEntryStatusIn]
      - in: query
        name: job[data][filter][advancedSearch][categoryIdEqual]
      - in: query
        name: job[data][filter][advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: job[data][filter][advancedSearch][contentLike]
      - in: query
        name: job[data][filter][advancedSearch][contentMultiLikeAnd]
      - in: query
        name: job[data][filter][advancedSearch][contentMultiLikeOr]
      - in: query
        name: job[data][filter][advancedSearch][cuePointsFreeText]
      - in: query
        name: job[data][filter][advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: job[data][filter][advancedSearch][cuePointTypeIn]
      - in: query
        name: job[data][filter][advancedSearch][depthGreaterThanEqual]
      - in: query
        name: job[data][filter][advancedSearch][distributionProfileId]
      - in: query
        name: job[data][filter][advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: job[data][filter][advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: job[data][filter][advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: job[data][filter][advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: job[data][filter][advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: job[data][filter][advancedSearch][extendedStatusIn]
      - in: query
        name: job[data][filter][advancedSearch][field]
      - in: query
        name: job[data][filter][advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: job[data][filter][advancedSearch][idEqual]
      - in: query
        name: job[data][filter][advancedSearch][idIn]
      - in: query
        name: job[data][filter][advancedSearch][indexIdGreaterThan]
      - in: query
        name: job[data][filter][advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: job[data][filter][advancedSearch][items]
      - in: query
        name: job[data][filter][advancedSearch][memberIdEq]
      - in: query
        name: job[data][filter][advancedSearch][memberIdIn]
      - in: query
        name: job[data][filter][advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: job[data][filter][advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: job[data][filter][advancedSearch][metadataProfileId]
      - in: query
        name: job[data][filter][advancedSearch][noDistributionProfiles]
      - in: query
        name: job[data][filter][advancedSearch][not]
      - in: query
        name: job[data][filter][advancedSearch][objectType]
      - in: query
        name: job[data][filter][advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: job[data][filter][advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: job[data][filter][advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: job[data][filter][advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: job[data][filter][advancedSearch][userIdEqual]
      - in: query
        name: job[data][filter][advancedSearch][userIdIn]
      - in: query
        name: job[data][filter][advancedSearch][value]
      - in: query
        name: job[data][filter][advancedSearch][watermarkId]
      - in: query
        name: job[data][filter][orderBy]
      - in: query
        name: job[data][flavorAssetId]
        description: Flavor asset to be ingested with the output
      - in: query
        name: job[data][flavorParamsId]
        description: Flavor params id to use for conversion
      - in: query
        name: job[data][flavorParamsOutputId]
      - in: query
        name: job[data][flavorParamsOutput][anamorphicPixels]
      - in: query
        name: job[data][flavorParamsOutput][aspectRatioProcessingMode]
      - in: query
        name: job[data][flavorParamsOutput][audioBitrate]
        description: The audio bitrate (in KBits) of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][audioChannels]
        description: The number of audio channels for downmixing
      - in: query
        name: job[data][flavorParamsOutput][audioCodec]
        description: 'Enum Type: `KalturaAudioCodec`The audio codec of the Flavor
          Params'
      - in: query
        name: job[data][flavorParamsOutput][audioSampleRate]
        description: The audio sample rate of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][clipDuration]
      - in: query
        name: job[data][flavorParamsOutput][clipOffset]
      - in: query
        name: job[data][flavorParamsOutput][commandLinesStr]
      - in: query
        name: job[data][flavorParamsOutput][contentAwareness]
      - in: query
        name: job[data][flavorParamsOutput][conversionEnginesExtraParams]
        description: The list of conversion engines extra params (separated with |)
      - in: query
        name: job[data][flavorParamsOutput][conversionEngines]
        description: The list of conversion engines (comma separated)
      - in: query
        name: job[data][flavorParamsOutput][deinterlice]
      - in: query
        name: job[data][flavorParamsOutput][densityHeight]
      - in: query
        name: job[data][flavorParamsOutput][densityWidth]
      - in: query
        name: job[data][flavorParamsOutput][depth]
      - in: query
        name: job[data][flavorParamsOutput][description]
        description: The description of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][engineVersion]
      - in: query
        name: job[data][flavorParamsOutput][flashVersion]
      - in: query
        name: job[data][flavorParamsOutput][flavorAssetId]
      - in: query
        name: job[data][flavorParamsOutput][flavorAssetVersion]
      - in: query
        name: job[data][flavorParamsOutput][flavorParamsId]
      - in: query
        name: job[data][flavorParamsOutput][flavorParamsVersion]
      - in: query
        name: job[data][flavorParamsOutput][forcedKeyFramesMode]
      - in: query
        name: job[data][flavorParamsOutput][forceFrameToMultiplication16]
      - in: query
        name: job[data][flavorParamsOutput][format]
        description: 'Enum Type: `KalturaContainerFormat`The container format of the
          Flavor Params'
      - in: query
        name: job[data][flavorParamsOutput][frameRate]
        description: The frame rate of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][gopSize]
        description: The gop size of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][height]
        description: The desired height of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][isAvoidForcedKeyFrames]
      - in: query
        name: job[data][flavorParamsOutput][isAvoidVideoShrinkBitrateToSource]
      - in: query
        name: job[data][flavorParamsOutput][isAvoidVideoShrinkFramesizeToSource]
      - in: query
        name: job[data][flavorParamsOutput][isCropIMX]
      - in: query
        name: job[data][flavorParamsOutput][isEncrypted]
      - in: query
        name: job[data][flavorParamsOutput][isGopInSec]
      - in: query
        name: job[data][flavorParamsOutput][isVideoFrameRateForLowBrAppleHls]
      - in: query
        name: job[data][flavorParamsOutput][maxFrameRate]
      - in: query
        name: job[data][flavorParamsOutput][mediaParserType]
        description: 'Enum Type: `KalturaMediaParserType`Media parser type to be used
          for post-conversion validation'
      - in: query
        name: job[data][flavorParamsOutput][multiStream]
      - in: query
        name: job[data][flavorParamsOutput][name]
        description: The name of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][objectType]
      - in: query
        name: job[data][flavorParamsOutput][operators]
      - in: query
        name: job[data][flavorParamsOutput][optimizationPolicy]
      - in: query
        name: job[data][flavorParamsOutput][partnerId]
      - in: query
        name: job[data][flavorParamsOutput][poly2Bitmap]
      - in: query
        name: job[data][flavorParamsOutput][readonly]
      - in: query
        name: job[data][flavorParamsOutput][readyBehavior]
      - in: query
        name: job[data][flavorParamsOutput][remoteStorageProfileIds]
        description: Comma seperated ids of remote storage profiles that the flavor
          distributed to, the distribution done by the conversion engine
      - in: query
        name: job[data][flavorParamsOutput][requiredPermissions]
      - in: query
        name: job[data][flavorParamsOutput][rotate]
      - in: query
        name: job[data][flavorParamsOutput][sizeHeight]
      - in: query
        name: job[data][flavorParamsOutput][sizeWidth]
      - in: query
        name: job[data][flavorParamsOutput][sourceAssetParamsIds]
        description: Comma seperated ids of source flavor params this flavor is created
          from
      - in: query
        name: job[data][flavorParamsOutput][sourceRemoteStorageProfileId]
        description: Id of remote storage profile that used to get the source, zero
          indicates Kaltura data center
      - in: query
        name: job[data][flavorParamsOutput][subtitlesData]
      - in: query
        name: job[data][flavorParamsOutput][systemName]
        description: System name of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][tags]
        description: The Flavor Params tags are used to identify the flavor for different
          usage (e
      - in: query
        name: job[data][flavorParamsOutput][twoPass]
      - in: query
        name: job[data][flavorParamsOutput][videoBitrateTolerance]
      - in: query
        name: job[data][flavorParamsOutput][videoBitrate]
        description: The video bitrate (in KBits) of the Flavor Params
      - in: query
        name: job[data][flavorParamsOutput][videoCodec]
        description: 'Enum Type: `KalturaVideoCodec`The video codec of the Flavor
          Params'
      - in: query
        name: job[data][flavorParamsOutput][videoConstantBitrate]
      - in: query
        name: job[data][flavorParamsOutput][watermarkData]
      - in: query
        name: job[data][flavorParamsOutput][widevineDistributionEndDate]
        description: License distribution window end date
      - in: query
        name: job[data][flavorParamsOutput][widevineDistributionStartDate]
        description: License distribution window start date
      - in: query
        name: job[data][flavorParamsOutput][width]
        description: The desired width of the Flavor Params
      - in: query
        name: job[data][flavors]
      - in: query
        name: job[data][force]
      - in: query
        name: job[data][fromEmail]
      - in: query
        name: job[data][fromName]
      - in: query
        name: job[data][fromPartnerId]
        description: Id of the partner to copy from
      - in: query
        name: job[data][ftpPassiveMode]
      - in: query
        name: job[data][inputFileSyncLocalPath]
      - in: query
        name: job[data][inputXmlLocalPath]
      - in: query
        name: job[data][inputXmlRemoteUrl]
      - in: query
        name: job[data][isHtml]
      - in: query
        name: job[data][keepDistributionItem]
        description: Flag signifying that the associated distribution item should
          not be moved to removed status
      - in: query
        name: job[data][ksType]
        description: 'Enum Type: `KalturaSessionType`'
      - in: query
        name: job[data][language]
        description: 'Enum Type: `KalturaLanguageCode`'
      - in: query
        name: job[data][lastCuePointSyncTime]
        description: last live to vod sync time
      - in: query
        name: job[data][lastMovedCategoryEntryPageIndex]
        description: Saves the last page index of the category entries filter pager     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastMovedCategoryId]
        description: Saves the last category id that its entries moved completely     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastMovedCategoryPageIndex]
        description: Saves the last page index of the child categories filter pager     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastSegmentDrift]
        description: last segment drift
      - in: query
        name: job[data][lastSegmentDuration]
        description: last Segment Duration
      - in: query
        name: job[data][lastUpdatedCategoryCreatedAt]
        description: Saves the last sub category creation date that was updated     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][lastUpdatedCategoryEntryCreatedAt]
        description: Saves the last category entry creation date that was updated     In
          case of crash the batch will restart from that point
      - in: query
        name: job[data][liveEntryId]
        description: live Entry Id
      - in: query
        name: job[data][localFileSyncPath]
      - in: query
        name: job[data][logFileSyncLocalPath]
      - in: query
        name: job[data][logFileSyncRemoteUrl]
      - in: query
        name: job[data][mailPriority]
      - in: query
        name: job[data][mailType]
        description: 'Enum Type: `KalturaMailType`'
      - in: query
        name: job[data][maxResults]
      - in: query
        name: job[data][mediaServerIndex]
        description: 'Enum Type: `KalturaEntryServerNodeType`Primary or secondary
          media server'
      - in: query
        name: job[data][mediaType]
      - in: query
        name: job[data][metadataId]
      - in: query
        name: job[data][metadataProfileId]
      - in: query
        name: job[data][method]
        description: 'Enum Type: `KalturaHttpNotificationMethod`Request method'
      - in: query
        name: job[data][minSendDate]
      - in: query
        name: job[data][modifiedAttributes]
      - in: query
        name: job[data][monitorSyncCompletion]
      - in: query
        name: job[data][moveFromChildren]
        description: All entries from all child categories will be moved as well
      - in: query
        name: job[data][multiLanaguageCaptionAssetId]
      - in: query
        name: job[data][notificationEmail]
      - in: query
        name: job[data][notificationResult]
      - in: query
        name: job[data][numberOfAttempts]
      - in: query
        name: job[data][objectData][conversionProfileId]
        description: Selected profile id for all bulk entries
      - in: query
        name: job[data][objectData][objectType]
      - in: query
        name: job[data][objectId]
      - in: query
        name: job[data][objectType]
      - in: query
        name: job[data][objType]
        description: 'Enum Type: `KalturaNotificationObjectType`'
      - in: query
        name: job[data][offset]
        description: Clipping offset in seconds
      - in: query
        name: job[data][outputPath]
      - in: query
        name: job[data][parsedSlug]
      - in: query
        name: job[data][parsedUserId]
      - in: query
        name: job[data][passPhrase]
      - in: query
        name: job[data][password]
        description: A password to use for the connection
      - in: query
        name: job[data][plays]
      - in: query
        name: job[data][primaryBroadcastingUrl]
      - in: query
        name: job[data][primaryContact]
      - in: query
        name: job[data][privateKey]
      - in: query
        name: job[data][protocol]
        description: http / https
      - in: query
        name: job[data][providerData][additionalParameters]
        description: additional parameters to send to Cielo24
      - in: query
        name: job[data][providerData][captionAssetFormats]
        description: Caption formats
      - in: query
        name: job[data][providerData][entryId]
        description: Entry ID
      - in: query
        name: job[data][providerData][exampleUrl]
        description: Just an example
      - in: query
        name: job[data][providerData][fidelity]
        description: 'Enum Type: `KalturaCielo24Fidelity`'
      - in: query
        name: job[data][providerData][flavorAssetId]
        description: Flavor ID
      - in: query
        name: job[data][providerData][metadataProfileId]
        description: ID of the metadata profile for the extracted term metadata
      - in: query
        name: job[data][providerData][objectType]
      - in: query
        name: job[data][providerData][priority]
        description: 'Enum Type: `KalturaCielo24Priority`'
      - in: query
        name: job[data][providerData][replaceMediaContent]
        description: should replace remote media content
      - in: query
        name: job[data][providerData][spokenLanguage]
        description: 'Enum Type: `KalturaLanguage`Transcript content language'
      - in: query
        name: job[data][providerData][transcriptAssetId]
        description: ID of the transcript asset
      - in: query
        name: job[data][providerData][transcriptId]
        description: input Transcript-asset ID
      - in: query
        name: job[data][providerData][voicebaseApiKey]
        description: Voicebase API key to fetch transcript tokens
      - in: query
        name: job[data][providerData][voicebaseApiPassword]
        description: Voicebase API password to fetch transcript tokens
      - in: query
        name: job[data][providerType]
        description: 'Enum Type: `KalturaIntegrationProviderType`'
      - in: query
        name: job[data][provisioningParams]
      - in: query
        name: job[data][publicKey]
      - in: query
        name: job[data][puserId]
        description: The id of the requesting user
      - in: query
        name: job[data][recipientEmail]
      - in: query
        name: job[data][recipientId]
        description: kuserId
      - in: query
        name: job[data][recipientName]
      - in: query
        name: job[data][referenceTime]
      - in: query
        name: job[data][remoteMediaId]
      - in: query
        name: job[data][resultsFilePath]
      - in: query
        name: job[data][returnVal]
      - in: query
        name: job[data][rtmp]
      - in: query
        name: job[data][s3Region]
      - in: query
        name: job[data][scanResult]
        description: 'Enum Type: `KalturaVirusScanJobResult`'
      - in: query
        name: job[data][secondaryBroadcastingUrl]
      - in: query
        name: job[data][secondaryContact]
      - in: query
        name: job[data][separator]
      - in: query
        name: job[data][serverPassPhrase]
      - in: query
        name: job[data][serverPassword]
      - in: query
        name: job[data][serverPrivateKey]
      - in: query
        name: job[data][serverPublicKey]
      - in: query
        name: job[data][serverUrl]
      - in: query
        name: job[data][serverUsername]
      - in: query
        name: job[data][server][dc]
        description: The dc of the server
      - in: query
        name: job[data][server][description]
      - in: query
        name: job[data][server][host]
      - in: query
        name: job[data][server][name]
      - in: query
        name: job[data][server][objectType]
      - in: query
        name: job[data][server][password]
      - in: query
        name: job[data][server][port]
      - in: query
        name: job[data][server][protocol]
        description: 'Enum Type: `KalturaActivitiBusinessProcessServerProtocol`'
      - in: query
        name: job[data][server][systemName]
      - in: query
        name: job[data][server][username]
      - in: query
        name: job[data][serviceToken]
      - in: query
        name: job[data][signatureType]
      - in: query
        name: job[data][signSecret]
        description: The secret to sign the notification with
      - in: query
        name: job[data][srcAssetId]
      - in: query
        name: job[data][srcAssetType]
        description: 'Enum Type: `KalturaAssetType`'
      - in: query
        name: job[data][srcCategoryId]
        description: Source category id
      - in: query
        name: job[data][srcFilePath]
        description: The recorded live media
      - in: query
        name: job[data][srcFileSyncId]
      - in: query
        name: job[data][srcFileSyncLocalPath]
      - in: query
        name: job[data][srcFileSyncRemoteUrl]
      - in: query
        name: job[data][srcFileSyncs]
      - in: query
        name: job[data][srcFiles]
      - in: query
        name: job[data][srcFileUrl]
      - in: query
        name: job[data][srcVersion]
      - in: query
        name: job[data][srcXslPath]
      - in: query
        name: job[data][sseKmsKeyId]
      - in: query
        name: job[data][sseType]
      - in: query
        name: job[data][sslCertificatePassword]
        description: The password required to use the certificate
      - in: query
        name: job[data][sslCertificateType]
        description: 'Enum Type: `KalturaHttpNotificationCertificateType`The format
          of the certificate'
      - in: query
        name: job[data][sslCertificate]
        description: SSL certificate to verify the peer with
      - in: query
        name: job[data][sslEngineDefault]
        description: The identifier for the crypto engine used for asymmetric crypto
          operations
      - in: query
        name: job[data][sslEngine]
        description: The identifier for the crypto engine of the private SSL key specified
          in ssl key
      - in: query
        name: job[data][sslKeyPassword]
        description: The secret password needed to use the private SSL key specified
          in ssl key
      - in: query
        name: job[data][sslKeyType]
        description: 'Enum Type: `KalturaHttpNotificationSslKeyType`The key type of
          the private SSL key specified in ssl key - PEM / DER / ENG'
      - in: query
        name: job[data][sslKey]
        description: Private SSL key
      - in: query
        name: job[data][sslVersion]
        description: 'Enum Type: `KalturaHttpNotificationSslVersion`The SSL version
          (2 or 3) to use'
      - in: query
        name: job[data][startObjectKey]
      - in: query
        name: job[data][status]
        description: 'Enum Type: `KalturaMailJobStatus`'
      - in: query
        name: job[data][streamID]
      - in: query
        name: job[data][streamName]
      - in: query
        name: job[data][streamType]
        description: 'Enum Type: `KalturaAkamaiUniversalStreamType`'
      - in: query
        name: job[data][subjectParams]
      - in: query
        name: job[data][syncMode]
        description: 'Enum Type: `KalturaWidevineRepositorySyncMode`'
      - in: query
        name: job[data][systemPassword]
      - in: query
        name: job[data][systemUserName]
      - in: query
        name: job[data][templateId]
      - in: query
        name: job[data][templatePath]
      - in: query
        name: job[data][thumbAssetId]
      - in: query
        name: job[data][thumbBitrate]
        description: The bit rate of last created thumbnail, will be used to comapare
          if this thumbnail is the best we can have
      - in: query
        name: job[data][thumbHeight]
        description: The height of last created thumbnail, will be used to comapare
          if this thumbnail is the best we can have
      - in: query
        name: job[data][thumbOffset]
        description: The position of the thumbnail in the media file
      - in: query
        name: job[data][thumbParamsOutputId]
      - in: query
        name: job[data][thumbPath]
      - in: query
        name: job[data][timeout]
        description: The maximum number of seconds to allow cURL functions to execute
      - in: query
        name: job[data][timeReference]
      - in: query
        name: job[data][timeZoneOffset]
      - in: query
        name: job[data][toPartnerId]
        description: Id of the partner to copy to
      - in: query
        name: job[data][totalVodDuration]
        description: total VOD Duration
      - in: query
        name: job[data][to][categoryUserFilter][categoryDirectMembers]
        description: Return the list of categoryUser that are not inherited from parent
          category - only the direct categoryUsers
      - in: query
        name: job[data][to][categoryUserFilter][categoryFullIdsEqual]
      - in: query
        name: job[data][to][categoryUserFilter][categoryFullIdsStartsWith]
      - in: query
        name: job[data][to][categoryUserFilter][categoryIdEqual]
      - in: query
        name: job[data][to][categoryUserFilter][categoryIdIn]
      - in: query
        name: job[data][to][categoryUserFilter][createdAtGreaterThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][createdAtLessThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][freeText]
        description: Free text search on user id or screen name
      - in: query
        name: job[data][to][categoryUserFilter][orderBy]
      - in: query
        name: job[data][to][categoryUserFilter][permissionLevelEqual]
        description: 'Enum Type: `KalturaCategoryUserPermissionLevel`'
      - in: query
        name: job[data][to][categoryUserFilter][permissionLevelIn]
      - in: query
        name: job[data][to][categoryUserFilter][permissionNamesMatchAnd]
      - in: query
        name: job[data][to][categoryUserFilter][permissionNamesMatchOr]
      - in: query
        name: job[data][to][categoryUserFilter][permissionNamesNotContains]
      - in: query
        name: job[data][to][categoryUserFilter][relatedGroupsByUserId]
        description: Return a list of categoryUser that related to the userId in this
          field by groups
      - in: query
        name: job[data][to][categoryUserFilter][statusEqual]
        description: 'Enum Type: `KalturaCategoryUserStatus`'
      - in: query
        name: job[data][to][categoryUserFilter][statusIn]
      - in: query
        name: job[data][to][categoryUserFilter][updatedAtGreaterThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][updatedAtLessThanOrEqual]
      - in: query
        name: job[data][to][categoryUserFilter][updateMethodEqual]
        description: 'Enum Type: `KalturaUpdateMethodType`'
      - in: query
        name: job[data][to][categoryUserFilter][updateMethodIn]
      - in: query
        name: job[data][to][categoryUserFilter][userIdEqual]
      - in: query
        name: job[data][to][categoryUserFilter][userIdIn]
      - in: query
        name: job[data][to][emailRecipients]
      - in: query
        name: job[data][to][filter][createdAtGreaterThanOrEqual]
      - in: query
        name: job[data][to][filter][createdAtLessThanOrEqual]
      - in: query
        name: job[data][to][filter][emailLike]
      - in: query
        name: job[data][to][filter][emailStartsWith]
      - in: query
        name: job[data][to][filter][firstNameOrLastNameStartsWith]
      - in: query
        name: job[data][to][filter][firstNameStartsWith]
      - in: query
        name: job[data][to][filter][idEqual]
      - in: query
        name: job[data][to][filter][idIn]
      - in: query
        name: job[data][to][filter][idOrScreenNameStartsWith]
      - in: query
        name: job[data][to][filter][isAdminEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: job[data][to][filter][lastNameStartsWith]
      - in: query
        name: job[data][to][filter][loginEnabledEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: job[data][to][filter][objectType]
      - in: query
        name: job[data][to][filter][orderBy]
      - in: query
        name: job[data][to][filter][partnerIdEqual]
      - in: query
        name: job[data][to][filter][permissionNamesMultiLikeAnd]
        description: Permission names filter expression
      - in: query
        name: job[data][to][filter][permissionNamesMultiLikeOr]
        description: Permission names filter expression
      - in: query
        name: job[data][to][filter][roleIdEqual]
      - in: query
        name: job[data][to][filter][roleIdsEqual]
      - in: query
        name: job[data][to][filter][roleIdsIn]
      - in: query
        name: job[data][to][filter][screenNameLike]
      - in: query
        name: job[data][to][filter][screenNameStartsWith]
      - in: query
        name: job[data][to][filter][statusEqual]
        description: 'Enum Type: `KalturaUserStatus`'
      - in: query
        name: job[data][to][filter][statusIn]
      - in: query
        name: job[data][to][filter][tagsMultiLikeAnd]
      - in: query
        name: job[data][to][filter][tagsMultiLikeOr]
      - in: query
        name: job[data][to][filter][typeEqual]
        description: 'Enum Type: `KalturaUserType`'
      - in: query
        name: job[data][to][filter][typeIn]
      - in: query
        name: job[data][to][objectType]
      - in: query
        name: job[data][typeAsString]
      - in: query
        name: job[data][type]
        description: 'Enum Type: `KalturaNotificationType`'
      - in: query
        name: job[data][url]
        description: Remote server URL
      - in: query
        name: job[data][userId]
      - in: query
        name: job[data][username]
        description: A username to use for the connection
      - in: query
        name: job[data][userRoles]
      - in: query
        name: job[data][views]
      - in: query
        name: job[data][virusFoundAction]
        description: 'Enum Type: `KalturaVirusFoundAction`'
      - in: query
        name: job[data][vodEntryId]
        description: $vod Entry Id
      - in: query
        name: job[data][webexHostId]
      - in: query
        name: job[data][wsdlPassword]
      - in: query
        name: job[data][wsdlUsername]
      - in: query
        name: job[data][wvAssetIds]
      - in: query
        name: job[entryId]
      - in: query
        name: job[entryName]
      - in: query
        name: job[jobSubType]
      - in: query
        name: lockKey[batchIndex]
      - in: query
        name: lockKey[schedulerId]
      - in: query
        name: lockKey[workerId]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - UpdateExclusiveJob
  /service/batch/action/updatePartnerLoadTable:
    get:
      summary: Get Service Batch Action Updatepartnerloadtable
      description: batch updatePartnerLoadTable action cleans the partner load table
      operationId: batch.updatePartnerLoadTable
      x-api-path-slug: servicebatchactionupdatepartnerloadtable-get
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
      - UpdatePartnerLoadTable
  /service/batchcontrol/action/configLoaded:
    get:
      summary: Get Service Batchcontrol Action Configloaded
      description: batch configLoaded action saves the configuration as loaded by
        a remote scheduler
      operationId: batchcontrol.configLoaded
      x-api-path-slug: servicebatchcontrolactionconfigloaded-get
      parameters:
      - in: query
        name: configParam
        description: The parameter that was loaded
      - in: query
        name: configParamPart
        description: The parameter part that was loaded
      - in: query
        name: configValue
        description: The value that was loaded
      - in: query
        name: No Name
      - in: query
        name: scheduler[configs]
      - in: query
        name: scheduler[configuredId]
        description: The id as configured in the batch config
      - in: query
        name: scheduler[host]
        description: The host name
      - in: query
        name: scheduler[name]
        description: The scheduler name
      - in: query
        name: scheduler[statuses]
      - in: query
        name: scheduler[workers]
      - in: query
        name: workerConfigId
        description: The id of the job that the configuration refers to, not mandatory
          if the configuration refers to the scheduler
      - in: query
        name: workerName
        description: The name of the job that the configuration refers to, not mandatory
          if the configuration refers to the scheduler
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - ConfigLoaded
  /service/batchcontrol/action/getCommand:
    get:
      summary: Get Service Batchcontrol Action Getcommand
      description: batch getCommand action returns the command with its current status
      operationId: batchcontrol.getCommand
      x-api-path-slug: servicebatchcontrolactiongetcommand-get
      parameters:
      - in: query
        name: commandId
        description: The id of the command
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - GetCommand
  /service/batchcontrol/action/getFullStatus:
    get:
      summary: Get Service Batchcontrol Action Getfullstatus
      description: batch getFullStatus action returns the status of all schedulers
        and queues
      operationId: batchcontrol.getFullStatus
      x-api-path-slug: servicebatchcontrolactiongetfullstatus-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - GetFullStatus
  /service/batchcontrol/action/kill:
    get:
      summary: Get Service Batchcontrol Action Kill
      description: batch kill action forces stop og a batch on a remote scheduler
      operationId: batchcontrol.kill
      x-api-path-slug: servicebatchcontrolactionkill-get
      parameters:
      - in: query
        name: adminId
        description: The id of the admin that called the stop
      - in: query
        name: batchIndex
        description: The index of the batch job process to be stopped
      - in: query
        name: cause
        description: The reason it was stopped
      - in: query
        name: No Name
      - in: query
        name: workerId
        description: The id of the job to be stopped
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - Kill
  /service/batchcontrol/action/listCommands:
    get:
      summary: Get Service Batchcontrol Action Listcommands
      description: list batch control commands
      operationId: batchcontrol.listCommands
      x-api-path-slug: servicebatchcontrolactionlistcommands-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[createdByIdEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaControlPanelCommandStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[targetTypeEqual]
        description: 'Enum Type: `KalturaControlPanelCommandTargetType`'
      - in: query
        name: filter[targetTypeIn]
      - in: query
        name: filter[typeEqual]
        description: 'Enum Type: `KalturaControlPanelCommandType`'
      - in: query
        name: filter[typeIn]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - ListCommands
  /service/batchcontrol/action/listSchedulers:
    get:
      summary: Get Service Batchcontrol Action Listschedulers
      description: list all Schedulers
      operationId: batchcontrol.listSchedulers
      x-api-path-slug: servicebatchcontrolactionlistschedulers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - ListSchedulers
  /service/batchcontrol/action/listWorkers:
    get:
      summary: Get Service Batchcontrol Action Listworkers
      description: list all Workers
      operationId: batchcontrol.listWorkers
      x-api-path-slug: servicebatchcontrolactionlistworkers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - ListWorkers
  /service/batchcontrol/action/reportStatus:
    get:
      summary: Get Service Batchcontrol Action Reportstatus
      description: batch reportStatus action saves the a status attribute from a remote
        scheduler and returns pending commands for the scheduler
      operationId: batchcontrol.reportStatus
      x-api-path-slug: servicebatchcontrolactionreportstatus-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: scheduler[configs]
      - in: query
        name: scheduler[configuredId]
        description: The id as configured in the batch config
      - in: query
        name: scheduler[host]
        description: The host name
      - in: query
        name: scheduler[name]
        description: The scheduler name
      - in: query
        name: scheduler[statuses]
      - in: query
        name: scheduler[workers]
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - ReportStatus
  /service/batchcontrol/action/setCommandResult:
    get:
      summary: Get Service Batchcontrol Action Setcommandresult
      description: batch setCommandResult action saves the results of a command as
        recieved from a remote scheduler
      operationId: batchcontrol.setCommandResult
      x-api-path-slug: servicebatchcontrolactionsetcommandresult-get
      parameters:
      - in: query
        name: commandId
        description: The id of the command
      - in: query
        name: errorDescription
        description: The description, important for failed commands
      - in: query
        name: No Name
      - in: query
        name: status
        description: 'Enum Type: `KalturaControlPanelCommandStatus`The status of the
          command'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - SetCommandResult
  /service/batchcontrol/action/setSchedulerConfig:
    get:
      summary: Get Service Batchcontrol Action Setschedulerconfig
      description: batch sets a configuration parameter to be loaded by a scheduler
      operationId: batchcontrol.setSchedulerConfig
      x-api-path-slug: servicebatchcontrolactionsetschedulerconfig-get
      parameters:
      - in: query
        name: adminId
        description: The id of the admin that called the setConfig
      - in: query
        name: cause
        description: The reason it was changed
      - in: query
        name: configParam
        description: The parameter to be set
      - in: query
        name: configParamPart
        description: The parameter part to be set - for additional params
      - in: query
        name: configValue
        description: The value to be set
      - in: query
        name: No Name
      - in: query
        name: schedulerId
        description: The id of the remote scheduler location
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - SetSchedulerConfig
  /service/batchcontrol/action/setWorkerConfig:
    get:
      summary: Get Service Batchcontrol Action Setworkerconfig
      description: batch sets a configuration parameter to be loaded by a worker
      operationId: batchcontrol.setWorkerConfig
      x-api-path-slug: servicebatchcontrolactionsetworkerconfig-get
      parameters:
      - in: query
        name: adminId
        description: The id of the admin that called the setConfig
      - in: query
        name: cause
        description: The reason it was changed
      - in: query
        name: configParam
        description: The parameter to be set
      - in: query
        name: configParamPart
        description: The parameter part to be set - for additional params
      - in: query
        name: configValue
        description: The value to be set
      - in: query
        name: No Name
      - in: query
        name: workerId
        description: The id of the job to be configured
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - SetWorkerConfig
  /service/batchcontrol/action/startWorker:
    get:
      summary: Get Service Batchcontrol Action Startworker
      description: batch start action starts a job
      operationId: batchcontrol.startWorker
      x-api-path-slug: servicebatchcontrolactionstartworker-get
      parameters:
      - in: query
        name: adminId
        description: The id of the admin that called the start
      - in: query
        name: cause
        description: The reason it was started
      - in: query
        name: No Name
      - in: query
        name: workerId
        description: The id of the job to be started
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batchcontrol
      - Action
      - StartWorker
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
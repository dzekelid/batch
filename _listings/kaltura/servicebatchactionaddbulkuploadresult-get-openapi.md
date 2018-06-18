---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Batch Action Addbulkuploadresult
  description: batch addBulkUploadResultAction action adds KalturaBulkUploadResult
    to the DB
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
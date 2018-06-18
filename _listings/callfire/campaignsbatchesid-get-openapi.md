---
swagger: "2.0"
x-collection-name: CallFire
x-complete: 0
info:
  title: Callfire Find a specific batch
  description: Returns a single Batch instance for a given batch id. This API is useful
    for determining the state of a validating batch
  termsOfService: https://www.callfire.com/legal/terms
  contact:
    name: CallFire
    url: https://www.callfire.com
    email: support@callfire.com
  version: 1.0.0
host: www.callfire.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /calls/broadcasts/{id}/batches:
    get:
      summary: Find batches in a call broadcast
      description: This endpoint will enable the user to page through all of the batches
        for a particular voice broadcast campaign
      operationId: getCallBroadcastBatches
      x-api-path-slug: callsbroadcastsidbatches-get
      parameters:
      - in: query
        name: fields
        description: Limit fields received in response
      - in: path
        name: id
        description: An id of a call broadcast
      - in: query
        name: limit
        description: To set the maximum number of records to return in a paged list
          response
      - in: query
        name: offset
        description: Offset to the start of a given page
      responses:
        200:
          description: OK
      tags:
      - Calls
      - Broadcasts
      - Batches
    post:
      summary: Add batches to a call broadcast
      description: The 'add batch' API allows user to add additional batches to an
        already created voice broadcast campaign. The added batch will go through
        the CallFire validation process, unlike in the recipients version of this
        API. That is why you can use the scrubDuplicates flag to remove duplicates
        from your batch. Batches may be added as a contact list id, a list of contact
        ids, or a list of numbers
      operationId: addCallBroadcastBatch
      x-api-path-slug: callsbroadcastsidbatches-post
      parameters:
      - in: body
        name: body
        description: A request object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: An id of a call broadcast
      - in: query
        name: strictValidation
        description: Turns on strict validation for recipients
      responses:
        200:
          description: OK
      tags:
      - Calls
      - Broadcasts
      - Batches
  /campaigns/batches/{id}:
    get:
      summary: Find a specific batch
      description: Returns a single Batch instance for a given batch id. This API
        is useful for determining the state of a validating batch
      operationId: getCampaignBatch
      x-api-path-slug: campaignsbatchesid-get
      parameters:
      - in: query
        name: fields
        description: Limit fields received in response
      - in: path
        name: id
        description: An id of a batch
      responses:
        200:
          description: OK
      tags:
      - Campaigns
      - Batches
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
---
swagger: "2.0"
x-collection-name: CallFire
x-complete: 1
info:
  title: CallFire
  description: callfire
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
    put:
      summary: Update a batch
      description: Updates a single Batch instance, currently batch can only be turned
        "on/off"
      operationId: updateCampaignBatch
      x-api-path-slug: campaignsbatchesid-put
      parameters:
      - in: body
        name: body
        description: A batch instance
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: An id of a batch to update
      responses:
        200:
          description: OK
      tags:
      - Campaigns
      - Batches
  /texts/broadcasts/{id}/batches:
    get:
      summary: Find batches in a text broadcast
      description: This endpoint will enable the user to page through all of the batches
        for a particular text broadcast campaign
      operationId: getTextBroadcastBatches
      x-api-path-slug: textsbroadcastsidbatches-get
      parameters:
      - in: query
        name: fields
        description: Limit fields received in response
      - in: path
        name: id
        description: An id of a text broadcast
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
      - Texts
      - Broadcasts
      - Batches
    post:
      summary: Add batches to a text broadcast
      description: Allows adding an extra batches to an already created text broadcast
        campaign. The batches which being  added pass the CallFire validation process
        (unlike in the recipients version of this API). That is why using of a scrubDuplicates
        flag remove duplicates from your batch. Batches may be added as a contact
        list id, a list of contact ids, or a list of numbers
      operationId: addTextBroadcastBatch
      x-api-path-slug: textsbroadcastsidbatches-post
      parameters:
      - in: body
        name: body
        description: A request object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: An id of a text broadcast
      - in: query
        name: strictValidation
        description: Turns on strict validation for recipients
      responses:
        200:
          description: OK
      tags:
      - Texts
      - Broadcasts
      - Batches
---
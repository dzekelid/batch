swagger: "2.0"
x-collection-name: Click Meter
x-complete: 1
info:
  title: Click Meter
  description: api-dashboard-for-clickmeter-api
  contact:
    name: Api Support
    url: http://www.clickmeter.com/api
    email: api@clickmeter.com
  version: v2
host: apiv2.clickmeter.com:80
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /conversions/{conversionId}/datapoints/batch/patch:
    put:
      summary: Modify the association between a conversion and multiple datapoints
      description: Modify the association between a conversion and multiple datapoints.
      operationId: putConversionsConversionDatapointsBatchPatch
      x-api-path-slug: conversionsconversioniddatapointsbatchpatch-put
      parameters:
      - in: path
        name: conversionId
        description: Id of the conversion
      - in: body
        name: data
        description: Patch requests
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Conversions
      - ConversionId
      - Datapoints
      - Batch
      - Patch
  /datapoints/batch:
    delete:
      summary: Delete multiple datapoints
      description: Delete multiple datapoints.
      operationId: deleteDatapointsBatch
      x-api-path-slug: datapointsbatch-delete
      parameters:
      - in: body
        name: batch
        description: A json containing the datapoints to delete
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Datapoints
      - Batch
    post:
      summary: Update multiple datapoints
      description: Update multiple datapoints.
      operationId: postDatapointsBatch
      x-api-path-slug: datapointsbatch-post
      parameters:
      - in: body
        name: batch
        description: A json containing the datapoints to update
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Datapoints
      - Batch
    put:
      summary: Create multiple datapoints
      description: Create multiple datapoints.
      operationId: putDatapointsBatch
      x-api-path-slug: datapointsbatch-put
      parameters:
      - in: body
        name: batch
        description: A json containing the datapoints to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Datapoints
      - Batch
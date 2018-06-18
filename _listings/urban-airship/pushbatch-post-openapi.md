---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 0
info:
  title: Urban Airship Post Push Batch
  description: Sends a push message to all the listed PINs. Each item in the list
    can contain 0 or many device_pins and 0 or many aliases or tags, and the blackberry
    payload is in the same format as for individual pushes.
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /push/batch:
    post:
      summary: Post Push Batch
      description: Sends a push message to all the listed PINs. Each item in the list
        can contain 0 or many device_pins and 0 or many aliases or tags, and the blackberry
        payload is in the same format as for individual pushes.
      operationId: push.batch.post
      x-api-path-slug: pushbatch-post
      parameters:
      - in: query
        name: Content-Type
        description: Content type
      - in: header
        name: Content-Type
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Push
      - Batch
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
---
swagger: "2.0"
x-collection-name: Cloud Elements
x-complete: 0
info:
  title: Cloud Elements - Dropbox For Business API Get Info Batch
  description: Get info batch.
  version: "1"
host: api.dropbox.com
basePath: /1/team
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /members/get_info_batch:
    post:
      summary: Get Info Batch
      description: Get info batch.
      operationId: postMembersGetInfoBatch
      x-api-path-slug: membersget-info-batch-post
      parameters:
      - in: query
        name: emails
        description: optional list of member emails
      - in: query
        name: external_ids
        description: optional list of external member IDs
      - in: query
        name: member_ids
        description: optional list of member IDs
      responses:
        200:
          description: OK
      tags:
      - Info
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
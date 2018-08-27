swagger: "2.0"
x-collection-name: Cloud Elements
x-complete: 1
info:
  title: zohocrm
  version: api-v2
host: console.cloud-elements.com
basePath: /elements/api-v2/hubs/crm
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
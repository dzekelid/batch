swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox Notify Appendix API v1
  description: the-dropbox-notify--is-a-part-of-dropbox-core-ap-with-a-separate-endpoint-for-notification-call-
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api-notify.dropbox.com
basePath: /1
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
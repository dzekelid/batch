---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 1
info:
  title: AWS EC2 Systems Manager API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateAssociationBatch:
    get:
      summary: Create Association Batch
      description: Associates the specified SSM document with the specified instances
        or targets.
      operationId: createAssociationBatch
      x-api-path-slug: actioncreateassociationbatch-get
      parameters:
      - in: query
        name: Entries
        description: One or more associations
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
      - Batch
---
---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Conversations API
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /conversations/batches:
    get:
      summary: Get running batches
      description: Get running batches.
      operationId: get-running-batches
      x-api-path-slug: conversationsbatches-get
      responses:
        200:
          description: OK
      tags:
      - Conversations
      - Batches
---
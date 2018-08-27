---
swagger: "2.0"
x-collection-name: Trello
x-complete: 0
info:
  title: Trello Get Batch
  description: Get batch.
  termsOfService: https://trello.com/legal
  contact:
    name: Trello
    url: https://trello.com/home
  version: "1.0"
host: trello.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /batch:
    get:
      summary: Get Batch
      description: Get batch.
      operationId: getBatch
      x-api-path-slug: batch-get
      parameters:
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      - in: query
        name: urls
        description: list of API v1 GET routes, not including the version prefix
      responses:
        200:
          description: OK
      tags:
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
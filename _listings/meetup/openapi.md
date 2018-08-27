swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /batch:
    post:
      summary: batch
      description: Performs multiple API requests in batch, useful for reducing HTTP
        network requests. This method is only available for OAuth authentication
      operationId: batch
      x-api-path-slug: batch-post
      parameters:
      - in: query
        name: requests
        description: JSON-encoding of multiple request objects as described in the
          parameter notes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Batch
---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  description: the-meetup-api-provides-simple-restful-http-and-streaming-interfaces-for-exploring-and-interacting-meetup-platform-from-your-own-apps--the-api-is-a-set-of-core-methods-and-a-common-request-format--these-are-combined-to-form-a-url-that-returns-the-information-you-want--
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
---
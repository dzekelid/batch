swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 1
info:
  title: Urban Airship
  description: the-urban-airships-api-powers-mobile-applications-with-push-rich-push-inapp-purchases-and-subscription-services-
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
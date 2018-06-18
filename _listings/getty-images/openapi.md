---
swagger: "2.0"
x-collection-name: Getty Images
x-complete: 1
info:
  title: Getty Images
  description: build-applications-using-the-worlds-most-powerful-imagery
  version: 1.0.0
host: api.gettyimages.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/usage-batches/{id}:
    put:
      summary: Reports Usage Batches
      description: "# Report Usage\r\n\r\nUse this endpoint to report the usages of
        a set of assets. The count of assets submitted in a single batch to this endpoint
        is limited to 1000. Note that all asset Ids specified must be valid or the
        operation will fail causing no usages to be recorded. In this case, you will
        need to remove the invalid asset Ids from the query request and re-submit
        the query.\r\n\r\n##  Quickstart\r\n\r\nYou'll need an API key and a [Resource
        Owner Grant](http://developers.gettyimages.com/en/authorization-faq.html)
        access token to use this resource.\r\nPlease see our [Getting Started](http://developers.gettyimages.com/en/getting-started.html)
        page for more information on how to sign up for an API key. \r\n\r\n\r\n_Note_:
        Date of use can be in any unambiguous date format."
      operationId: Usage_Put
      x-api-path-slug: v3usagebatchesid-put
      parameters:
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: path
        name: id
        description: Specifies a unique batch transaction id to identify the report
      - in: body
        name: request
        description: Specifies up to 1000 sets of asset Id, usage count, and date
          of use to submit usages for
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Images
      - Batches
---
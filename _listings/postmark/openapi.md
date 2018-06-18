---
swagger: "2.0"
x-collection-name: Postmark
x-complete: 1
info:
  title: Postmark
  description: send-emails-retrieve-bounces-and-start-accepting-inbound-emails-all-via-an-easytouse-http-api-
  version: 1.0.0
host: spamcheck.postmarkapp.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /email/batch:
    parameters:
      summary: Parameters Email Batch
      description: Parameters email batch.
      operationId: parametersEmailBatch
      x-api-path-slug: emailbatch-parameters
      responses:
        200:
          description: OK
      tags:
      - Email
      - Batch
    post:
      summary: Post Email Batch
      description: "While Postmark is focused on transactional email, we understand
        that developers with higher volumes or processing time constraints need to
        send their messages in batches. To facilitate this we provide a batching endpoint
        that permits you to send up to 500 well-formed Postmark messages in a single
        API call.\n                    \nThe format of the batched message is a JSON
        array containing multiple message requests like the following example:\n[\n
        \   {From: 'sender@example.com', To: 'receiver1@example.com', Subject: 'Postmark
        test #1', HtmlBody: 'Hello dear Postmark user.'},\n    {From: 'sender@example.com',
        To: 'receiver2@example.com', Subject: 'Postmark test #2', HtmlBody: 'Hello
        dear Postmark user.'}\n]\n\nYou can use SSL encryption by issuing requests
        to https://api.postmarkapp.com/email/batch.\n\nSimilarly, you will receive
        a matching JSON array containing each response for the messages you sent in
        your batched call:\n\n[\n    {\n        \"ErrorCode\" : 0,\n        \"Message\"
        : \"OK\",\n        \"MessageID\" : \"b7bc2f4a-e38e-4336-af7d-e6c392c2f817\",\n
        \       \"SubmittedAt\" : \"2010-11-26T12:01:05.1794748-05:00\",\n        \"To\"
        : \"receiver1@example.com\"\n    },\n    {\n        \"ErrorCode\" : 0,\n        \"Message\"
        : \"OK\",\n        \"MessageID\" : \"e2ecbbfc-fe12-463d-b933-9fe22915106d\",\n
        \       \"SubmittedAt\" : \"2010-11-26T12:01:05.1794748-05:00\",\n        \"To\"
        : \"receiver2@example.com\"\n    },\n]"
      operationId: postEmailBatch
      x-api-path-slug: emailbatch-post
      parameters:
      - in: query
        name: Accept
        description: The accepted type for the response
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: Content-Type
        description: The content type of the request
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Email
      - Batch
---
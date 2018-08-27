swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mail/batch:
    post:
      summary: Add Mail Batch
      description: "**This endpoint allows you to generate a new batch ID. This batch
        ID can be associated with scheduled sends via the mail/send endpoint.**\n\nIf
        you set the SMTPAPI header `batch_id`, it allows you to then associate multiple
        scheduled mail/send requests together with the same ID. Then at anytime up
        to 10 minutes before the schedule date, you can cancel all of the mail/send
        requests that have this batch ID by calling the Cancel Scheduled Send endpoint.
        \n\nMore Information:\n\n* [Scheduling Parameters > Batch ID](https://sendgrid.com/docs/API_Reference/SMTP_API/scheduling_parameters.html)"
      operationId: mail.batch.post
      x-api-path-slug: mailbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Batch
  /mail/batch/{batch_id}:
    get:
      summary: Get Mail Batch Batch
      description: "**This endpoint allows you to validate a batch ID.**\n\nIf you
        set the SMTPAPI header `batch_id`, it allows you to then associate multiple
        scheduled mail/send requests together with the same ID. Then at anytime up
        to 10 minutes before the schedule date, you can cancel all of the mail/send
        requests that have this batch ID by calling the Cancel Scheduled Send endpoint.
        \n\nMore Information:\n\n* [Scheduling Parameters > Batch ID](https://sendgrid.com/docs/API_Reference/SMTP_API/scheduling_parameters.html)"
      operationId: mail.batch.batch_id.get
      x-api-path-slug: mailbatchbatch-id-get
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Batch
      - Batch
  /user/scheduled_sends/{batch_id}:
    delete:
      summary: Delete User Scheduled Sends Batch
      description: |-
        **This endpoint allows you to delete the cancellation/pause of a scheduled send.**

        The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.
      operationId: user.scheduled_sends.batch_id.delete
      x-api-path-slug: userscheduled-sendsbatch-id-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Scheduled
      - Sends
      - Batch
    get:
      summary: Get User Scheduled Sends Batch
      description: |-
        **This endpoint allows you to retrieve the cancel/paused scheduled send information for a specific `batch_id`.**

        The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.
      operationId: user.scheduled_sends.batch_id.get
      x-api-path-slug: userscheduled-sendsbatch-id-get
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Scheduled
      - Sends
      - Batch
    patch:
      summary: Patch User Scheduled Sends Batch
      description: |-
        **This endpoint allows you to update the status of a scheduled send for the given `batch_id`.**

        The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.
      operationId: user.scheduled_sends.batch_id.patch
      x-api-path-slug: userscheduled-sendsbatch-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Scheduled
      - Sends
      - Batch
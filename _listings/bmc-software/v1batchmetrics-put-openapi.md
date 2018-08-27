---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 0
info:
  title: BMC Software API Update metrics batch
  version: 1.0.0
  description: Updates a batch of metrics
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/batch:
    post:
      summary: Perform batch
      description: |-
        Allows making an arbitrary set of API calls.    All calls are made in parallel.
        The query string parameter <em>?series</em> can be used to override this behavior and call the API in series stopping at the first error.
      operationId: perform-batch
      x-api-path-slug: v1batch-post
      responses:
        200:
          description: OK
      tags:
      - Batch
  /v1/batch/metrics:
    post:
      summary: Create metrics batch
      description: Creates metrics, but in a batch
      operationId: create-metrics-batch
      x-api-path-slug: v1batchmetrics-post
      responses:
        200:
          description: OK
      tags:
      - Batch
    put:
      summary: Update metrics batch
      description: Updates a batch of metrics
      operationId: update-metrics-batch
      x-api-path-slug: v1batchmetrics-put
      parameters:
      - in: formData
        name: |-
          type
          Type of metric, could be a device metric, a plugin metric or any arbitrary type
        description: descriptionDescription of the metric
        type: string
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
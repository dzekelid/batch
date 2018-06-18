---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Photos Geo Batch Correct Location
  description: Correct the places hierarchy for all the photos for a user at a given
    latitude, longitude and accuracy. Batch corrections are processed in a delayed
    queue so it may take a few minutes before the changes are reflected in a user's
    photos.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.photos.geo.batchCorrectLocation:
    post:
      summary: Photos Geo Batch Correct Location
      description: Correct the places hierarchy for all the photos for a user at a
        given latitude, longitude and accuracy. Batch corrections are processed in
        a delayed queue so it may take a few minutes before the changes are reflected
        in a user's photos.
      operationId: postRestMethodFlickr.photos.geo.batchcorrectlocation
      x-api-path-slug: restmethodflickr-photos-geo-batchcorrectlocation-post
      parameters:
      - in: query
        name: accuracy
        description: Recorded accuracy level of the photos to be updated
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: lat
        description: The latitude of the photos to be updated whose valid range is
          -90 to 90
      - in: query
        name: lon
        description: The longitude of the photos to be updated whose valid range is
          -180 to 180
      - in: query
        name: place_id
        description: A Flickr Places ID
      - in: query
        name: woe_id
        description: A Where on Earch (WOE) ID
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Geo
      - BatchCorrectLocation
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
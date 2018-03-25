---
swagger: "2.0"
info:
  title: Eventbrite
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /events/:
    post:
      summary: Makes a new event, and returns an event for the specified event.
      description: Makes a new event, and returns an event for the specified event
      operationId: makes-a-new-event-and-returns-an-event-for-the-specified-event
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - events
definitions: []
x-collection-name: Eventbrite
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
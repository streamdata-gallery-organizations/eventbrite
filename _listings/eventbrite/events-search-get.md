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
  /events/search/:
    get:
      summary: Allows you to retrieve a paginated response of public event objects
        from across Eventbrite?s directory, regardless of wh
      description: Allows you to retrieve a paginated response of public event objects
        from across Eventbrite?s directory, regardless of which user owns the event
      operationId: allows-you-to-retrieve-a-paginated-response-of-public-event-objects-from-across-eventbrites-director
      parameters:
      - in: query
        name: q
        description: Return events matching the given keywords
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
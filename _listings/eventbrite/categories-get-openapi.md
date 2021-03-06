---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Categories
  description: |-
    Returns a list of category as categories, including
    subcategories nested.
  version: 1.0.0
host: www.eventbriteapi.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /events/:
    post:
      summary: Add Events
      description: Makes a new event, and returns an event for the specified event.
      operationId: postEvents
      x-api-path-slug: events-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: event.capacity
        description: Set specific capacity (if omitted, sums ticket capacities)
        type: query
      - in: query
        name: event.category_id
        description: The category (vertical) of the event
        type: query
      - in: query
        name: event.currency
        description: Event currency (3 letter code)
        type: query
      - in: query
        name: event.description.html
        description: The description on the event page
        type: query
      - in: query
        name: event.end.timezone
        description: End time timezone (Olson format)
        type: query
      - in: query
        name: event.end.utc
        description: The end time of the event
        type: query
      - in: query
        name: event.format_id
        description: The format (general type) of the event
        type: query
      - in: query
        name: event.hide_end_date
        description: Whether the end date should be hidden
        type: query
      - in: query
        name: event.hide_start_date
        description: Whether the start date should be hidden
        type: query
      - in: query
        name: event.invite_only
        description: Only invited users can see the event page
        type: query
      - in: query
        name: event.is_reserved_seating
        description: If the event is reserved seating
        type: query
      - in: query
        name: event.listed
        description: If the event is publicly listed and searchable
        type: query
      - in: query
        name: event.logo.id
        description: (Deprecated) The logo for the event
        type: query
      - in: query
        name: event.logo_id
        description: The logo for the event
        type: query
      - in: query
        name: event.name.html
        description: The name of the event
        type: query
      - in: query
        name: event.online_event
        description: Is the event online-only (no venue)?
        type: query
      - in: query
        name: event.organizer_id
        description: The ID of the organizer of this event
        type: query
      - in: query
        name: event.password
        description: Password needed to see the event in unlisted mode
        type: query
      - in: query
        name: event.shareable
        description: If users can share the event on social media
        type: query
      - in: query
        name: event.show_pick_a_seat
        description: For reserved seating event, if attendees can pick their seats
        type: query
      - in: query
        name: event.show_remaining
        description: If the remaining number of tickets is publicly visible on the
          event page
        type: query
      - in: query
        name: event.show_seatmap_thumbnail
        description: For reserved seating event, if venue map thumbnail visible on
          the event page
        type: query
      - in: query
        name: event.source
        description: Source of the event (defaults to API)
        type: query
      - in: query
        name: event.start.timezone
        description: Start time timezone (Olson format)
        type: query
      - in: query
        name: event.start.utc
        description: The start time of the event
        type: query
      - in: query
        name: event.subcategory_id
        description: The subcategory of the event (US only)
        type: query
      - in: query
        name: event.venue_id
        description: The ID of a previously-created venue to associate with this event
        type: query
      responses:
        200:
          description: OK
      tags:
      - Events
  /events/search/:
    get:
      summary: Get Events Search
      description: Allows you to retrieve a paginated response of public event objects
        from across Eventbrite?s directory, regardless of which user owns the event.
      operationId: getEventsSearch
      x-api-path-slug: eventssearch-get
      parameters:
      - in: query
        name: categories
        description: Only return events under the given category IDs
        type: query
      - in: query
        name: date_modified.keyword
        description: Only return events with modified dates within the given keyword
          date range
        type: query
      - in: query
        name: date_modified.range_end
        description: Only return events with modified dates before the given UTC date
        type: query
      - in: query
        name: date_modified.range_start
        description: Only return events with modified dates after the given UTC date
        type: query
      - in: query
        name: formats
        description: Only return events with the given format IDs
        type: query
      - in: query
        name: high_affinity_categories
        description: Make search results prefer events in these categories
        type: query
      - in: query
        name: include_all_series_instances
        description: Boolean for whether or not you want to see all instances of repeating
          events in search results
        type: query
      - in: query
        name: include_unavailable_events
        description: Boolean for whether or not you want to see events without tickets
          on sale
        type: query
      - in: query
        name: incorporate_user_affinities
        description: Incorporate additional information from the user&#8217;s historic
          preferences
        type: query
      - in: query
        name: location.address
        description: The address of the location you want to search for events around
        type: query
      - in: query
        name: location.latitude
        description: The latitude of of the location you want to search for events
          around
        type: query
      - in: query
        name: location.longitude
        description: The longitude of the location you want to search for events around
        type: query
      - in: query
        name: location.viewport.northeast.latitude
        description: The latitude of the northeast corner of a viewport
        type: query
      - in: query
        name: location.viewport.northeast.longitude
        description: The longitude of the northeast corner of a viewport
        type: query
      - in: query
        name: location.viewport.southwest.latitude
        description: The latitude of the southwest corner of a viewport
        type: query
      - in: query
        name: location.viewport.southwest.longitude
        description: The longitude of the southwest corner of a viewport
        type: query
      - in: query
        name: location.within
        description: The distance you want to search around the given location
        type: query
      - in: query
        name: organizer.id
        description: Only return events organized by the given Organizer ID
        type: query
      - in: query
        name: price
        description: Only return events that are &#8220;free&#8221; or &#8220;paid&#8221;
        type: query
      - in: query
        name: q
        description: Return events matching the given keywords
      - in: query
        name: search_type
        description: Use the preconfigured settings for this type of search - Current
          option is &#8220;promoted&#8221;
        type: query
      - in: query
        name: sort_by
        description: Parameter you want to sort by - options are &#8220;date&#8221;,
          &#8220;distance&#8221; and &#8220;best&#8221;
        type: query
      - in: query
        name: start_date.keyword
        description: Only return events with start dates within the given keyword
          date range
        type: query
      - in: query
        name: start_date.range_end
        description: Only return events with start dates before the given date
        type: query
      - in: query
        name: start_date.range_start
        description: Only return events with start dates after the given date
        type: query
      - in: query
        name: subcategories
        description: Only return events under the given subcategory IDs
        type: query
      - in: query
        name: tracking_code
        description: Append the given tracking_code to the event URLs returned
        type: query
      - in: query
        name: user.id
        description: Only return events owned by the given User ID
        type: query
      responses:
        200:
          description: OK
      tags:
      - Events
      - Search
  /events/{id}:
    get:
      summary: Get Events
      description: Returns an event for the specified event. Many of Eventbrite?s
        API use cases resolve around pulling details of a specific event within an
        Eventbrite account.
      operationId: getEvents
      x-api-path-slug: eventsid-get
      parameters:
      - in: path
        name: id
        description: Event Id
      responses:
        200:
          description: OK
      tags:
      - Events
    post:
      summary: Add Events
      description: Updates an event. Returns an event for the specified event.
      operationId: postEvents
      x-api-path-slug: eventsid-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Event Id
      responses:
        200:
          description: OK
      tags:
      - Events
  /categories/:
    get:
      summary: Get Categories
      description: |-
        Returns a list of category as categories, including
        subcategories nested.
      operationId: getCategories
      x-api-path-slug: categories-get
      responses:
        200:
          description: OK
      tags:
      - Categories
x-streamrank:
  polling_total_time_average: "0.23"
  polling_size_download_average: "4775.05"
  streaming_total_time_average: "0.13"
  streaming_size_download_average: "2387.52"
  change_yes: "3"
  change_no: "2365"
  time_percentage: "45"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
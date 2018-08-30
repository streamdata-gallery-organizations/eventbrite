{
  "info": {
    "name": "Eventbrite Get Events Event  Tracking Beacons",
    "_postman_id": "293f710e-64e5-432f-a43d-635cc8684f9e",
    "description": "Returns the list of tracking_beacon for the event :event_id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracking",
      "item": [
        {
          "id": "fcada103-e62b-49c5-bdb5-9f71104c954e",
          "name": "postTrackingBeacons",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/tracking_beacons/?event_id=%7B%7D&pixel_id=%7B%7D&tracking_type=%7B%7D&triggers=%7B%7D&user_id=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Makes a new tracking beacon. Returns an tracking_beacon as tracking_beacon. Either event_id or user_id is required for each tracking beacon. If the event_id is provided, the tracking pixel will fire only for that event. If the user_id is provided, the tracking pixel will fire for all events organized by that user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abfe8d7f-432f-4c9c-af73-0793a4231c8e"
            }
          ]
        },
        {
          "id": "fb704179-1773-44ca-aa8e-781e290cb377",
          "name": "getTrackingBeaconsTrackingBeacons",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/tracking_beacons/:tracking_beacons_id/?return_fmt=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the tracking_beacon with the specified :tracking_beacons_id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da8a5260-9de9-4002-a6ba-b160dd76fa36"
            }
          ]
        },
        {
          "id": "e66e3c88-0495-428e-8e31-fb9896e6a2b3",
          "name": "postTrackingBeaconsTrackingBeacons",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/tracking_beacons/:tracking_beacons_id/?event_id=%7B%7D&pixel_id=%7B%7D&tracking_type=%7B%7D&triggers=%7B%7D&user_id=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the tracking_beacons with the specified :tracking_beacons_id. Though event_id and user_id are not individually required, it is a requirement to have a tracking beacon where either one must exist. Returns an tracking_beacon as tracking_beacon."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84744003-e844-477f-81d8-09f2afd2c65a"
            }
          ]
        },
        {
          "id": "9c15741f-79e0-4249-8209-bbc95b896809",
          "name": "deleteTrackingBeaconsTrackingBeacons",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/tracking_beacons/:tracking_beacons_id/",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete the tracking_beacons with the specified :tracking_beacons_id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c29f264a-86f2-4c1b-b758-676e634a7529"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "6af61fb4-9843-470a-a7dc-3b3031d54485",
          "name": "getEventsEventTrackingBeacons",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/events/:event_id/tracking_beacons/?return_fmt=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of tracking_beacon for the event :event_id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74ecfbcd-d1e2-4eed-b31a-b43fb3b12bbf"
            }
          ]
        }
      ]
    }
  ]
}
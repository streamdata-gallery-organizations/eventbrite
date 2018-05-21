{
  "info": {
    "name": "Eventbrite Delete Tracking Beacons Tracking Beacons",
    "_postman_id": "99890605-68f5-4d49-805a-314f0fc22d28",
    "description": "Delete the tracking_beacons with the specified :tracking_beacons_id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracking",
      "item": [
        {
          "id": "b2eb7b71-2d8d-400a-bd47-48a30db02d43",
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
              "id": "d58ece3a-b988-483e-a548-2e15508891a4"
            }
          ]
        },
        {
          "id": "0ccb4012-ac18-485a-983c-4a6cda869dd4",
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
              "id": "2c80bf8b-f124-4113-aa2c-6053133c90ad"
            }
          ]
        },
        {
          "id": "cfc99cb2-8519-4e60-960b-d4ee3b15ba28",
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
              "id": "f8bdd95e-deac-418e-a843-f29614e12f82"
            }
          ]
        },
        {
          "id": "26083ea7-1c5c-4194-9e50-104540681ed8",
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
              "id": "4b9ed0da-8da8-4be0-9673-f63b74829689"
            }
          ]
        }
      ]
    }
  ]
}
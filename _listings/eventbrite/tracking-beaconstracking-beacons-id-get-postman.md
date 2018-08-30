{
  "info": {
    "name": "Eventbrite Get Tracking Beacons Tracking Beacons",
    "_postman_id": "52f0b8e9-2df8-4039-9ec2-de2107365df9",
    "description": "Returns the tracking_beacon with the specified :tracking_beacons_id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracking",
      "item": [
        {
          "id": "a29ac502-8524-4d92-93c1-2d22b9abe78e",
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
              "id": "a361e2a7-579e-4fab-9570-00545b1dd8f0"
            }
          ]
        },
        {
          "id": "15346d00-370c-4173-8de6-f85a5bba0ecb",
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
              "id": "fc1b0d42-eb62-430c-8a94-4482a96e3ea5"
            }
          ]
        }
      ]
    }
  ]
}
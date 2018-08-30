{
  "info": {
    "name": "Eventbrite Add Tracking Beacons Tracking Beacons",
    "_postman_id": "2c39ebea-9bb0-460d-a098-4a87a7247528",
    "description": "Updates the tracking_beacons with the specified :tracking_beacons_id. Though event_id and user_id are not individually required, it is a requirement to have a tracking beacon where either one must exist. Returns an tracking_beacon as tracking_beacon.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracking",
      "item": [
        {
          "id": "bebf1e9c-ab0e-40d9-a662-1e80eb13f13e",
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
              "id": "11f043a1-5b1f-44a2-b179-8de04287dee6"
            }
          ]
        },
        {
          "id": "088e461d-88f5-47c7-a4f6-ce2e2a8dfde6",
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
              "id": "d97a8c32-b6e9-4203-b075-4798ad1b08f7"
            }
          ]
        },
        {
          "id": "cc11dd29-b309-487a-9ea5-4fa6d6ef2a80",
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
              "id": "b5648ab8-69e9-4c5e-a6db-33014d497684"
            }
          ]
        }
      ]
    }
  ]
}
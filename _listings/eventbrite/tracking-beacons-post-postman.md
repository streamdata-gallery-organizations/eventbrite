{
  "info": {
    "name": "Eventbrite Add Tracking Beacons",
    "_postman_id": "fd47e944-126e-4d47-bb71-778af575b8a2",
    "description": "Makes a new tracking beacon. Returns an tracking_beacon as tracking_beacon. Either event_id or user_id is required for each tracking beacon. If the event_id is provided, the tracking pixel will fire only for that event. If the user_id is provided, the tracking pixel will fire for all events organized by that user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracking",
      "item": [
        {
          "id": "143fc907-7e99-45ef-9b61-571493cf75d5",
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
              "id": "0e2a0d9c-e156-436d-9dc3-4e19a0b7d4af"
            }
          ]
        }
      ]
    }
  ]
}
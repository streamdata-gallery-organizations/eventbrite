{
  "info": {
    "name": "Eventbrite Get Events  Ticket Classes",
    "_postman_id": "e429c547-db35-4a9f-b940-d95ff60226ce",
    "description": "Returns a paginated response with a key of\nticket_classes, containing a list of ticket_class.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Events",
      "item": [
        {
          "id": "a6e32c11-ee29-402d-9d1b-b080853b6d93",
          "name": "getEventsTicketClasses",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.eventbriteapi.com",
              "path": [
                "v3",
                "events/:id/ticket_classes/"
              ],
              "query": [
                {
                  "key": "pos",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated response with a key of\nticket_classes, containing a list of ticket_class."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8fd59fbd-3d2e-4f1d-9de5-9c9e7d392d27"
            }
          ]
        }
      ]
    }
  ]
}
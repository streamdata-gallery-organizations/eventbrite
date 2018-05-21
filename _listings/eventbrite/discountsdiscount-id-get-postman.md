{
  "info": {
    "name": "Eventbrite Get Discounts Discount",
    "_postman_id": "b3cca822-5ea4-4871-a521-6a8b23db67b5",
    "description": "Returns the cross_event_discount with the specified :discount_id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Discounts",
      "item": [
        {
          "id": "e3926d03-d746-411c-b284-3945069efe61",
          "name": "getDiscountsDiscount",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/discounts/:discount_id/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the cross_event_discount with the specified :discount_id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9284f5fb-614d-4217-a93b-193ffcb0483f"
            }
          ]
        }
      ]
    }
  ]
}
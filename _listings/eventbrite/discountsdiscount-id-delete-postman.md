{
  "info": {
    "name": "Eventbrite Delete Discounts Discount",
    "_postman_id": "0b22e527-dc1c-4f5c-8e5c-10aeb92cceb1",
    "description": "Deletes the cross_event_discount with the specified :discount_id.\nOnly unused discounts can be deleted.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Discounts",
      "item": [
        {
          "id": "8e99d05e-f192-4dfe-b8ab-ebd052d8f901",
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
              "id": "f4b6a808-fcd6-4baa-b87f-071e12f33133"
            }
          ]
        },
        {
          "id": "35beeafa-83fb-4fa7-afa1-630e822bd2ce",
          "name": "postDiscountsDiscount",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/discounts/:discount_id/?discount.amount_off=%7B%7D&discount.code=%7B%7D&discount.end_date=%7B%7D&discount.end_date_relative=%7B%7D&discount.hold_ids=%7B%7D&discount.percent_off=%7B%7D&discount.quantity_available=%7B%7D&discount.start_date=%7B%7D&discount.start_date_relative=%7B%7D&discount.ticket_class_ids=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the discount with the specified :discount_id. Returns the updated cross_event_discount. The fields sent are the ones that are going to be updated, the fields that are not sent will be unchanged. The same conditions and notes for the discount creation apply."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2eb058b4-cf97-4a33-8243-d54495c53046"
            }
          ]
        },
        {
          "id": "eed0ca0d-1ceb-4a56-bdb7-207a9b2ebedf",
          "name": "deleteDiscountsDiscount",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/discounts/:discount_id/",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the cross_event_discount with the specified :discount_id.\nOnly unused discounts can be deleted."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d200a0b-35db-427c-b547-dd7be9359433"
            }
          ]
        },
        {
          "id": "7f964fd4-e0c1-4c96-ad04-a199822dd9c8",
          "name": "postDiscounts",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/discounts/?discount.amount_off=%7B%7D&discount.code=%7B%7D&discount.end_date=%7B%7D&discount.end_date_relative=%7B%7D&discount.event_id=%7B%7D&discount.hold_ids=%7B%7D&discount.percent_off=%7B%7D&discount.quantity_available=%7B%7D&discount.start_date=%7B%7D&discount.start_date_relative=%7B%7D&discount.ticket_class_ids=%7B%7D&discount.ticket_group_id=%7B%7D&discount.type=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a discount. Returns the created cross_event_discount."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc388f78-d25f-412e-92e1-7a195578cfce"
            }
          ]
        }
      ]
    }
  ]
}
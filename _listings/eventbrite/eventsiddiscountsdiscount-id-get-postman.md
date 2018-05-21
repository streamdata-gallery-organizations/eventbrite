{
  "info": {
    "name": "Eventbrite Get Events  Discounts Discount",
    "_postman_id": "405762d4-be7f-4c09-ab85-216421989364",
    "description": "Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Discounts",
      "item": [
        {
          "id": "78450630-9539-4bb4-9832-f3561313afde",
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
              "id": "104303fc-fdf7-4ceb-a23a-de863781d27c"
            }
          ]
        },
        {
          "id": "bfcf0e24-5122-41c4-91bc-77004cd710d2",
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
              "id": "8a87a203-b341-4ee2-bb30-60bd0c99494f"
            }
          ]
        },
        {
          "id": "19400845-0092-464b-8d83-de973b6a55c9",
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
              "id": "e1479690-8307-46b6-bc0d-50ee1aeb86be"
            }
          ]
        },
        {
          "id": "18a3f1d1-62ba-48e5-a9c4-b0a84cb32574",
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
              "id": "0da9eaa9-b2d3-4264-8160-19b2c89bc32d"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "33caed8e-3511-4750-a40a-653d7925b2fa",
          "name": "getEventsDiscounts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.eventbriteapi.com",
              "path": [
                "v3",
                "events/:id/discounts/"
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
            "description": "Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31271bdd-75f9-43dd-9577-36fef95ecb0c"
            }
          ]
        },
        {
          "id": "c598d612-0659-4c80-8b48-9437a31d9090",
          "name": "postEventsDiscounts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.eventbriteapi.com",
              "path": [
                "v3",
                "events/:id/discounts/"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a69f16f4-7a47-4b06-92a4-6b16deb14a50"
            }
          ]
        },
        {
          "id": "1689f15c-afb0-499f-a424-224387bd3deb",
          "name": "getEventsDiscountsDiscount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.eventbriteapi.com",
              "path": [
                "v3",
                "events/:id/discounts/:discount_id/"
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
            "description": "Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "041d0696-0607-44c9-8373-2dfe4dca54cc"
            }
          ]
        }
      ]
    }
  ]
}
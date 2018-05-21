{
  "info": {
    "name": "Eventbrite Get Checkout Settings Countries Currencies",
    "_postman_id": "1bfc1925-9768-4409-a894-8ad20af3aad4",
    "description": "Get the countries and currencies which are supported by Eventbrite for ticket payment",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Checkout",
      "item": [
        {
          "id": "488726fa-fd0b-4dc4-8389-32bda2f4c83c",
          "name": "getCheckoutSettingsCountriesCurrencies",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/checkout_settings/countries_currencies/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the countries and currencies which are supported by Eventbrite for ticket payment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02e961f3-ccea-4514-8c08-779ba01a01c5"
            }
          ]
        }
      ]
    }
  ]
}
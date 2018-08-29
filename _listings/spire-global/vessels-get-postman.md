{
  "info": {
    "name": "Spire Find Vessels Arriving Between Date/Time Window",
    "_postman_id": "7d66f503-cb07-47f0-9d9c-5b9135a9d2f8",
    "description": "Returns all vessels with an ETA greater than the `arriving_after` and ETA less than the `arriving_before` parameter.\n\nQuery can also be used without the `arriving_before` parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Vessels",
      "item": [
        {
          "id": "38b33d02-5c49-4ad8-b279-0ce1375d4482",
          "name": "VesselsGet10",
          "request": {
            "url": "http://ais.spire.com/vessels?arriving_after=%7B%7D&arriving_before=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all vessels with an ETA greater than the `arriving_after` and ETA less than the `arriving_before` parameter.\n\nQuery can also be used without the `arriving_before` parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c42e156-3028-4246-b94e-be2be2a62421"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Spire Get Individual Vessel",
    "_postman_id": "683cf2a6-5fe1-4299-b9d9-37f8d8c86d80",
    "description": "Returns individual ship details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Vessels",
      "item": [
        {
          "id": "55eb9b36-8e54-496f-9f20-735bf85b925d",
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
              "id": "84f181a8-3371-4bc7-869f-623ce55deb3f"
            }
          ]
        },
        {
          "id": "e67b1f98-2ccd-42a8-8b79-115747d89316",
          "name": "VesselsA5b738b4Faf04a7e9a871c0ccfb123d2Get",
          "request": {
            "url": "http://ais.spire.com/vessels/a5b738b4-faf0-4a7e-9a87-1c0ccfb123d2",
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
            "description": "Returns individual ship details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b7ddf5f-ffc3-4f39-abdf-fc3362331ebd"
            }
          ]
        }
      ]
    }
  ]
}
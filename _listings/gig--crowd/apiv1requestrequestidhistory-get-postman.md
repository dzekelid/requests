{
  "info": {
    "name": "GIGANDCROWD Get Request Requestid History",
    "_postman_id": "70200194-ac14-4062-8ab4-7a9ea0722c72",
    "description": "Get request requestid history.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Gigme",
      "item": [
        {
          "id": "6b42d96d-659c-45f2-8a6f-d1d0a8b5eb6e",
          "name": "getApiV1GigmeEventHistory",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/gigme/event/history",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get gigme event history."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e263f57f-6f4b-4f0b-b88c-0c2eb38d844b"
            }
          ]
        }
      ]
    },
    {
      "name": "Request",
      "item": [
        {
          "id": "3121369c-ebf5-41c1-b348-adf7155df0af",
          "name": "getApiV1RequestRequestHistory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/request/:requestId/history"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get request requestid history."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93d559d5-404a-48dd-bdca-f016c824d2b0"
            }
          ]
        }
      ]
    }
  ]
}
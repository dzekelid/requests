{
  "info": {
    "name": "Eventbrite Add Refund Requests",
    "_postman_id": "1495f88e-89fd-4964-a7b6-8d439d808ada",
    "description": "Creates a refund-request for a specific order. Each element in items is a refund-item",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Refund",
      "item": [
        {
          "id": "4cc9642c-d660-4f5b-bd59-08b20855175a",
          "name": "getRefundRequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.eventbriteapi.com",
              "path": [
                "v3",
                "refund_requests/:id/"
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
            "description": "Gets a refund-request for the specified refund request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2bd46f0d-fddd-403b-b749-c74129cd8dce"
            }
          ]
        },
        {
          "id": "ba3f84fc-c243-40c4-81c0-b51fed6c5947",
          "name": "postRefundRequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.eventbriteapi.com",
              "path": [
                "v3",
                "refund_requests/:id/"
              ],
              "query": [
                {
                  "key": "from_email",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "items",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "message",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "reason",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Update a refund-request for a specific order. Each element in items is a refund-item"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef5b81c2-f575-4511-b630-d5e01bbd503b"
            }
          ]
        },
        {
          "id": "d91aa2fa-84bc-4fff-b9e8-d71a6de77af3",
          "name": "postRefundRequests1",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/refund_requests/?from_email=%7B%7D&from_name=%7B%7D&items=%7B%7D&message=%7B%7D&reason=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a refund-request for a specific order. Each element in items is a refund-item"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f06e724-783e-4b5a-9d1e-6fe6d4161ae0"
            }
          ]
        }
      ]
    }
  ]
}
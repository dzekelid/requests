{
  "info": {
    "name": "Eventbrite Add Refund Requests",
    "_postman_id": "1f2e6723-4a42-4dd4-ab40-d0c07f1e0957",
    "description": "Update a refund-request for a specific order. Each element in items is a refund-item",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Refund",
      "item": [
        {
          "id": "e4dd0c24-b2ea-473e-8886-2e0c5455eebd",
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
              "id": "99156def-96af-44fa-bd0c-95f63b5be36d"
            }
          ]
        },
        {
          "id": "7d340c00-202e-481f-86af-266dae4f9e3b",
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
              "id": "f548e6d5-95b9-4ad6-821f-7a0cdcb19fe1"
            }
          ]
        }
      ]
    }
  ]
}
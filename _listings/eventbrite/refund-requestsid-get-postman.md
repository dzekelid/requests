{
  "info": {
    "name": "Eventbrite Get Refund Requests",
    "_postman_id": "adbe1a52-6206-411b-b7c9-6a9f3bdb6749",
    "description": "Gets a refund-request for the specified refund request.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Refund",
      "item": [
        {
          "id": "20916912-d324-441c-bfe8-dd47bd0b5005",
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
              "id": "4e026a98-cfcb-4bb4-bff7-3936fd291ebd"
            }
          ]
        }
      ]
    }
  ]
}
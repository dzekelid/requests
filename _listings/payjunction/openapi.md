swagger: "2.0"
x-collection-name: PayJunction
x-complete: 1
info:
  title: PayJunction API Basic
  description: todo-add-description
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /smartterminals/requests/{requestPaymentId}:
    get:
      summary: Get Smart Terminals Requests
      description: "Gets the status of a Smart Terminal payment request by querying
        the requestPaymentId returned by POST /smartterminals/{smartterminalId}/request-payment\n\nThe
        status of a payment request can be queried up to 1 day after the Smart Terminal
        payment request has been completed. After this cut off the requestPaymentId
        is purged and will return a 404 Not Found when queried. \n\nIn order to discourage
        busy polling, requests to this endpoint are rate limited to 1 request every
        2 seconds per request."
      operationId: SmartterminalsRequestsByRequestPaymentIdGet
      x-api-path-slug: smartterminalsrequestsrequestpaymentid-get
      parameters:
      - in: path
        name: requestPaymentId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Smart
      - Terminals
      - Requests
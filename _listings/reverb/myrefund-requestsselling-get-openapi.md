---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: reverb Get My Refund Requests Selling
  description: Get a list of refund requests as a seller
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/orders/selling/{order_id}/refund_requests:
    post:
      summary: Post My Orders Selling Order Refund Requests
      description: Post my orders selling order refund requests.
      operationId: postMyOrdersSellingOrderRefundRequests
      x-api-path-slug: myorderssellingorder-idrefund-requests-post
      parameters:
      - in: path
        name: order_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Orders
      - Selling
      - Order
      - Id
      - Refund
      - Requests
  /my/refund_requests/selling:
    get:
      summary: Get My Refund Requests Selling
      description: Get a list of refund requests as a seller
      operationId: getMyRefundRequestsSelling
      x-api-path-slug: myrefund-requestsselling-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Refund
      - Requests
      - Selling
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
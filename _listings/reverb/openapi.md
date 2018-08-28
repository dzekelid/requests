swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
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
  /my/refund_requests/selling/{id}:
    put:
      summary: Put My Refund Requests Selling
      description: Update a refund request for a sold order
      operationId: putMyRefundRequestsSelling
      x-api-path-slug: myrefund-requestssellingid-put
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Refund
      - Requests
      - Selling
      - Id
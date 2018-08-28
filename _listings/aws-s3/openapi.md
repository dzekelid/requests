swagger: "2.0"
x-collection-name: AWS S3
x-complete: 1
info:
  title: No Title
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ?requestPayment:
    get:
      summary: GET Bucket requestPayment
      description: This implementation of the GET operation uses therequestPayment
        subresource to return the request paymentconfiguration of a bucket
      operationId: get-bucket-requestpayment
      x-api-path-slug: requestpayment-get
      responses:
        200:
          description: OK
      tags:
      - Bucket
      - RequestPayment
    put:
      summary: PUT Bucket requestPayment
      description: This implementation of the PUT operation uses therequestPayment
        subresource to set the request paymentconfiguration of a bucket
      operationId: put-bucket-requestpayment
      x-api-path-slug: requestpayment-put
      responses:
        200:
          description: OK
      tags:
      - Bucket
      - RequestPayment
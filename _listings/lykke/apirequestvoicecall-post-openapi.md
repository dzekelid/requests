---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Requestvoicecall
  version: 1.0.0
  description: Add api requestvoicecall.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/offchain/requests:
    get:
      summary: Get API Offchain Requests
      description: Get api offchain requests.
      operationId: ApiOffchainRequestsGet
      x-api-path-slug: apioffchainrequests-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Requests
  /api/offchain/requestTransfer:
    post:
      summary: Add API Offchain Requesttransfer
      description: Add api offchain requesttransfer.
      operationId: ApiOffchainRequestTransferPost
      x-api-path-slug: apioffchainrequesttransfer-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Requesttransfer
  /api/RequestVoiceCall:
    post:
      summary: Add API Requestvoicecall
      description: Add api requestvoicecall.
      operationId: ApiRequestVoiceCallPost
      x-api-path-slug: apirequestvoicecall-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Requestvoicecall
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
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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
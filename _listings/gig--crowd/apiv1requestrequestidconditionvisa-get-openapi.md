---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Request Requestid Condition Visa
  version: 1.0.0
  description: Get request requestid condition visa.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/notify/requests:
    get:
      summary: Get Notify Requests
      description: Get notify requests.
      operationId: getApiV1NotifyRequests
      x-api-path-slug: apiv1notifyrequests-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Notify
      - Requests
  /api/v1/request/requests/{requestId}/logs:
    get:
      summary: Get Request Requests Requestid Logs
      description: Get request requests requestid logs.
      operationId: getApiV1RequestRequestsRequestLogs
      x-api-path-slug: apiv1requestrequestsrequestidlogs-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requests
      - Requestid
      - Logs
  /api/v1/payment/promocode/{requestId}:
    post:
      summary: Post Payment Promocode Requestid
      description: Post payment promocode requestid.
      operationId: postApiV1PaymentPromocodeRequest
      x-api-path-slug: apiv1paymentpromocoderequestid-post
      parameters:
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: requestId
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Promocode
      - Requestid
  /api/v1/request/{requestId}:
    get:
      summary: Get Request Requestid
      description: Get request requestid.
      operationId: getApiV1RequestRequest
      x-api-path-slug: apiv1requestrequestid-get
      parameters:
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
  /api/v1/request/{requestId}/history:
    get:
      summary: Get Request Requestid History
      description: Get request requestid history.
      operationId: getApiV1RequestRequestHistory
      x-api-path-slug: apiv1requestrequestidhistory-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - History
  /api/v1/request/{requestId}/comments:
    get:
      summary: Get Request Requestid Comments
      description: Get request requestid comments.
      operationId: getApiV1RequestRequestComments
      x-api-path-slug: apiv1requestrequestidcomments-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Comments
    post:
      summary: Post Request Requestid Comments
      description: Post request requestid comments.
      operationId: postApiV1RequestRequestComments
      x-api-path-slug: apiv1requestrequestidcomments-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Comments
  /api/v1/request/{requestId}/files:
    get:
      summary: Get Request Requestid Files
      description: Get request requestid files.
      operationId: getApiV1RequestRequestFiles
      x-api-path-slug: apiv1requestrequestidfiles-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Files
    post:
      summary: Post Request Requestid Files
      description: Post request requestid files.
      operationId: postApiV1RequestRequestFiles
      x-api-path-slug: apiv1requestrequestidfiles-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: file
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Files
  /api/v1/request/{requestId}/files/{fileId}:
    get:
      summary: Get Request Requestid Files Fileid
      description: Get request requestid files fileid.
      operationId: getApiV1RequestRequestFilesFile
      x-api-path-slug: apiv1requestrequestidfilesfileid-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: fileId
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Files
      - Fileid
    delete:
      summary: Delete Request Requestid Files Fileid
      description: Delete request requestid files fileid.
      operationId: deleteApiV1RequestRequestFilesFile
      x-api-path-slug: apiv1requestrequestidfilesfileid-delete
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: fileId
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Files
      - Fileid
  /api/v1/request/{requestId}/condition/visa:
    get:
      summary: Get Request Requestid Condition Visa
      description: Get request requestid condition visa.
      operationId: getApiV1RequestRequestConditionVisa
      x-api-path-slug: apiv1requestrequestidconditionvisa-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Visa
    post:
      summary: Post Request Requestid Condition Visa
      description: Post request requestid condition visa.
      operationId: postApiV1RequestRequestConditionVisa
      x-api-path-slug: apiv1requestrequestidconditionvisa-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Visa
  /api/v1/request/{requestId}/condition/travel:
    get:
      summary: Get Request Requestid Condition Travel
      description: Get request requestid condition travel.
      operationId: getApiV1RequestRequestConditionTravel
      x-api-path-slug: apiv1requestrequestidconditiontravel-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Travel
    post:
      summary: Post Request Requestid Condition Travel
      description: Post request requestid condition travel.
      operationId: postApiV1RequestRequestConditionTravel
      x-api-path-slug: apiv1requestrequestidconditiontravel-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Travel
  /api/v1/request/{requestId}/condition/residence:
    get:
      summary: Get Request Requestid Condition Resence
      description: Get request requestid condition resence.
      operationId: getApiV1RequestRequestConditionResence
      x-api-path-slug: apiv1requestrequestidconditionresidence-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Resence
    post:
      summary: Post Request Requestid Condition Resence
      description: Post request requestid condition resence.
      operationId: postApiV1RequestRequestConditionResence
      x-api-path-slug: apiv1requestrequestidconditionresidence-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Resence
  /api/v1/request/{requestId}/condition/delivery:
    get:
      summary: Get Request Requestid Condition Delivery
      description: Get request requestid condition delivery.
      operationId: getApiV1RequestRequestConditionDelivery
      x-api-path-slug: apiv1requestrequestidconditiondelivery-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Delivery
    post:
      summary: Post Request Requestid Condition Delivery
      description: Post request requestid condition delivery.
      operationId: postApiV1RequestRequestConditionDelivery
      x-api-path-slug: apiv1requestrequestidconditiondelivery-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Delivery
  /api/v1/request/{requestId}/condition/{condition}/confirm:
    post:
      summary: Post Request Requestid Condition Condition Confirm
      description: Post request requestid condition condition confirm.
      operationId: postApiV1RequestRequestConditionConditionConfirm
      x-api-path-slug: apiv1requestrequestidconditionconditionconfirm-post
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: condition
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Condition
      - Confirm
  /api/v1/request/{requestId}/condition/{condition}/reject:
    post:
      summary: Post Request Requestid Condition Condition Reject
      description: Post request requestid condition condition reject.
      operationId: postApiV1RequestRequestConditionConditionReject
      x-api-path-slug: apiv1requestrequestidconditionconditionreject-post
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: condition
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Condition
      - Reject
  /api/v1/request/{requestId}/condition/{condition}/documents:
    get:
      summary: Get Request Requestid Condition Condition Documents
      description: Get request requestid condition condition documents.
      operationId: getApiV1RequestRequestConditionConditionDocuments
      x-api-path-slug: apiv1requestrequestidconditionconditiondocuments-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: condition
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Condition
      - Documents
    post:
      summary: Post Request Requestid Condition Condition Documents
      description: Post request requestid condition condition documents.
      operationId: postApiV1RequestRequestConditionConditionDocuments
      x-api-path-slug: apiv1requestrequestidconditionconditiondocuments-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: file
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Condition
      - Condition
      - Documents
  /api/v1/request/{requestId}/art/{artistId}/rider:
    get:
      summary: Get Request Requestid Art Artistid Rer
      description: Get request requestid art artistid rer.
      operationId: getApiV1RequestRequestArtArtistRer
      x-api-path-slug: apiv1requestrequestidartartistidrider-get
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Art
      - Artistid
      - Rer
  /api/v1/request/{requestId}/art/{artistId}/rider/home:
    get:
      summary: Get Request Requestid Art Artistid Rer Home
      description: Get request requestid art artistid rer home.
      operationId: getApiV1RequestRequestArtArtistRerHome
      x-api-path-slug: apiv1requestrequestidartartistidriderhome-get
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Art
      - Artistid
      - Rer
      - Home
  /api/v1/request/{requestId}/art/{artistId}/presskit/{photoId}:
    get:
      summary: Get Request Requestid Art Artistid Presskit Photoid
      description: Get request requestid art artistid presskit photoid.
      operationId: getApiV1RequestRequestArtArtistPresskitPhoto
      x-api-path-slug: apiv1requestrequestidartartistidpresskitphotoid-get
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: photoId
      - in: path
        name: requestId
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Art
      - Artistid
      - Presskit
      - Photoid
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
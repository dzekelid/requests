---
swagger: "2.0"
x-collection-name: MockLab
x-complete: 0
info:
  title: MockLab Post Requests Find
  version: 1.0.0
  description: Retrieve details of requests logged in the journal matching the specified
    criteria
basePath: /__admin
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /requests:
    delete:
      summary: Delete Requests
      description: Delete all received requests
      operationId: deleteRequests
      x-api-path-slug: requests-delete
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Requests
    get:
      summary: Get Requests
      description: Get received requests
      operationId: getRequests
      x-api-path-slug: requests-get
      parameters:
      - in: query
        name: limit
        description: The maximum number of results to return
      - in: query
        name: since
        description: Only return logged requests after this date
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Requests
  /requests/count:
    post:
      summary: Post Requests Count
      description: Count requests logged in the journal matching the specified criteria
      operationId: postRequestsCount
      x-api-path-slug: requestscount-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Requests
      - Count
  /requests/find:
    post:
      summary: Post Requests Find
      description: Retrieve details of requests logged in the journal matching the
        specified criteria
      operationId: postRequestsFind
      x-api-path-slug: requestsfind-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Requests
      - Find
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
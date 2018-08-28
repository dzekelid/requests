swagger: "2.0"
x-collection-name: MockLab
x-complete: 1
info:
  title: WireMock
  version: 1.0.0
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
  /requests/reset:
    post:
      summary: Post Requests Reset
      description: Empty the request journal
      operationId: postRequestsReset
      x-api-path-slug: requestsreset-post
      responses:
        200:
          description: Successful response
      tags:
      - Requests
      - Reset
  /requests/unmatched:
    get:
      summary: Get Requests Unmatched
      description: Get details of logged requests that weren't matched by any stub
        mapping
      operationId: getRequestsUnmatched
      x-api-path-slug: requestsunmatched-get
      responses:
        200:
          description: Successful response
      tags:
      - Requests
      - Unmatched
  /requests/unmatched/near-misses:
    get:
      summary: Get Requests Unmatched Near Misses
      description: Retrieve near-misses for all unmatched requests
      operationId: getRequestsUnmatchedNearMisses
      x-api-path-slug: requestsunmatchednearmisses-get
      responses:
        200:
          description: Successful response
      tags:
      - Requests
      - Unmatched
      - Near
      - Misses
  /requests/{requestId}:
    get:
      summary: Get Requests Requestid
      description: Get requests requestid.
      operationId: getRequestsRequest
      x-api-path-slug: requestsrequestid-get
      parameters:
      - in: path
        name: requestId
        description: The UUID of the logged request
      responses:
        200:
          description: Successful response
      tags:
      - Requests
      - Requestid
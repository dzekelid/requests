---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Get Me Friendrequests
  description: A person&#039;s pending friend requests.
  termsOfService: https://www.facebook.com/policies/
  version: 1.0.0
host: graph.facebook.com
basePath: /v3.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /&#123;user-id&#125;/apprequests:
    get:
      summary: Get User Apprequests
      description: User Apprequests
      operationId: getUserApprequests
      x-api-path-slug: 123userid125apprequests-get
      parameters:
      - in: query
        name: "100"
        description: Invalid parameter
        type: string
      - in: query
        name: "159"
        description: Invalid protocol, must be https
        type: string
      - in: query
        name: "200"
        description: Permissions error
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Apprequests
  /&#123;user-id&#125;/favorite_requests:
    get:
      summary: Get User Favorite Requests
      description: User Favorite Requests
      operationId: getUserFavoriteRequests
      x-api-path-slug: 123userid125favorite-requests-get
      parameters:
      - in: query
        name: "100"
        description: Invalid parameter
        type: string
      - in: query
        name: "200"
        description: Permissions error
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Favorite
      - Requests
  /me/friendrequests:
    get:
      summary: Get Me Friendrequests
      description: A person&#039;s pending friend requests.
      operationId: getMeFriendrequests
      x-api-path-slug: mefriendrequests-get
      parameters:
      - in: query
        name: created_time
        description: Time at which the friend request was created
        type: string
      - in: query
        name: from
        description: The person who sent the friend request
        type: string
      - in: query
        name: message
        description: Message provided by the sender when they sent the request
        type: string
      - in: query
        name: to
        description: The person to whom the friend request was sent
        type: string
      - in: query
        name: unread
        description: Whether the user has read the friend request or not
        type: string
      responses:
        200:
          description: OK
      tags:
      - Me
      - Friendrequests
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
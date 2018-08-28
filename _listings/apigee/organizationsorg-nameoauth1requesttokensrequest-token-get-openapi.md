---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 0
info:
  title: Apigee Edge Get Organizations Name Oauth1 Requesttokens Request Token
  description: Gets the Oauth 1.0 a request token for the speficied consumer key.
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/oauth1/requesttokens/{request_token}:
    get:
      summary: Get Organizations Name Oauth1 Requesttokens Request Token
      description: Gets the Oauth 1.0 a request token for the speficied consumer key.
      operationId: getOrganizationsOrgNameOauth1RequesttokensRequestToken
      x-api-path-slug: organizationsorg-nameoauth1requesttokensrequest-token-get
      parameters:
      - in: query
        name: consumerKey
        description: Mention valid consumer key
      - in: query
        name: Content-Type
        description: Specify Content Type
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: request_token
        description: Mention the request token
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth1
      - Requesttokens
      - Request
      - Token
    post:
      summary: Post Organizations Name Oauth1 Requesttokens Request Token
      description: Revokes an OAuth 1.0 a request token.
      operationId: postOrganizationsOrgNameOauth1RequesttokensRequestToken
      x-api-path-slug: organizationsorg-nameoauth1requesttokensrequest-token-post
      parameters:
      - in: query
        name: action
        description: Mention action as revoke
      - in: query
        name: Content-Type
        description: Specify Content Type
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: request_token
        description: Mention the request token
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth1
      - Requesttokens
      - Request
      - Token
    delete:
      summary: Delete Organizations Name Oauth1 Requesttokens Request Token
      description: Deletes the request token specified.
      operationId: deleteOrganizationsOrgNameOauth1RequesttokensRequestToken
      x-api-path-slug: organizationsorg-nameoauth1requesttokensrequest-token-delete
      parameters:
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: request_token
        description: Mention the request token
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth1
      - Requesttokens
      - Request
      - Token
  /organizations/{org_name}/oauth1/requesttokens:
    get:
      summary: Get Organizations Name Oauth1 Requesttokens
      description: Returns list of all OAuth 1.0a request.
      operationId: getOrganizationsOrgNameOauth1Requesttokens
      x-api-path-slug: organizationsorg-nameoauth1requesttokens-get
      parameters:
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth1
      - Requesttokens
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
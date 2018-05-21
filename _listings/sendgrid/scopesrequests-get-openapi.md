---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Get Scopes Requests
  description: |-
    This endpoint allows you to retrieve a list of all recent access requests.

    **Note:** The Response Header's 'link' parameter will include pagination info. For example:

    link: ```<https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="first"; title="1", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=10>; rel="last"; title="2", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="prev"; title="1"```
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /scopes/requests:
    get:
      summary: Get Scopes Requests
      description: |-
        This endpoint allows you to retrieve a list of all recent access requests.

        **Note:** The Response Header's 'link' parameter will include pagination info. For example:

        link: ```<https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="first"; title="1", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=10>; rel="last"; title="2", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="prev"; title="1"```
      operationId: scopes.requests.get
      x-api-path-slug: scopesrequests-get
      parameters:
      - in: query
        name: limit
        description: Optional field to limit the number of results returned
      - in: query
        name: offset
        description: Optional beginning point in the list to retrieve from
      responses:
        200:
          description: OK
      tags:
      - Email
      - Scopes
      - Requests
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
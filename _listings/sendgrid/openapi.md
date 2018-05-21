---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  description: the-sendgrid-web-api-v3-documentation-this-is-the-entirety-of-the-documented-v3-endpoints-we-have-updated-all-the-descriptions-parameters-requests-and-responses-authentication-every-endpoint-requires-authentication-in-the-form-of-an-authorization-header-authorization-bearer-api-key
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
  /scopes/requests/{request_id}:
    delete:
      summary: Delete Scopes Requests Request
      description: |-
        This endpoint allows you to deny an attempt to access your account.

        **Note:** Only teammate admins may delete a teammate's access request.
      operationId: scopes.requests.request_id.delete
      x-api-path-slug: scopesrequestsrequest-id-delete
      responses:
        200:
          description: OK
      tags:
      - Email
      - Scopes
      - Requests
      - Request
  /scopes/requests/{request_id}/approve:
    patch:
      summary: Patch Scopes Requests Request  Approve
      description: "This endpoint allows you to approve an access attempt.\n\n**Note:**
        Only teammate admins may approve another teammate\u2019s access request."
      operationId: scopes.requests.request_id.approve.patch
      x-api-path-slug: scopesrequestsrequest-idapprove-patch
      responses:
        200:
          description: OK
      tags:
      - Email
      - Scopes
      - Requests
      - Request
      - ""
      - Approve
---
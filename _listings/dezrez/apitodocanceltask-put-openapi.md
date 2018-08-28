---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Cancel the Task. Used for cancelling the Lead Requests.
  version: 1.0.0
  description: Cancel the task. used for cancelling the lead requests..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/todo/canceltask:
    put:
      summary: Cancel the Task. Used for cancelling the Lead Requests.
      description: Cancel the task. used for cancelling the lead requests..
      operationId: DefaultToDo_CancelTaskBycancelTask
      x-api-path-slug: apitodocanceltask-put
      parameters:
      - in: body
        name: cancelTask
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Task
      - ""
      - Usedcancelling
      - Lead
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
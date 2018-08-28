---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Set the requested lot number for a property auction role.
  version: 1.0.0
  description: Set the requested lot number for a property auction role..
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
  /api/todo/cancelleadandtask:
    put:
      summary: Cancel the Task. Used for cancelling the Lead Requests.
      description: Cancel the task. used for cancelling the lead requests..
      operationId: DefaultToDo_CancelLeadAndTaskBycancelLead
      x-api-path-slug: apitodocancelleadandtask-put
      parameters:
      - in: body
        name: cancelLead
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
  /api/role/auction/{id}/setrequestedlotnumber:
    post:
      summary: Set the requested lot number for a property auction role.
      description: Set the requested lot number for a property auction role..
      operationId: AuctionRole_SetRequestedLotNumberByidBylotNumber
      x-api-path-slug: apiroleauctionidsetrequestedlotnumber-post
      parameters:
      - in: path
        name: id
        description: the id of the role
      - in: query
        name: lotNumber
        description: the requested lot number
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Requested
      - Lot
      - Numbera
      - Property
      - Auction
      - Role
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
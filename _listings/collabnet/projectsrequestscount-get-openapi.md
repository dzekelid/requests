---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Gets the number of pending project
    requests
  version: 1.0.0
  description: Gets the number of pending project requests.
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/requests/count:
    get:
      summary: Gets the number of pending project requests
      description: Gets the number of pending project requests.
      operationId: getProjectRequestCount
      x-api-path-slug: projectsrequestscount-get
      responses:
        200:
          description: OK
      tags:
      - Number
      - Of
      - Pending
      - Project
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
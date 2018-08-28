---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Analytics Framework Get the analytic validation status by validation
    request id.
  version: 1.0.0
  description: Returns the analytic validation status (one of 'queued,' 'processing,'
    or 'completed' and the result from running the analytic (when status is 'completed').
host: predix-acs.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/catalog/analytics/{id}/validation/{validationRequestId}:
    get:
      summary: Get the analytic validation status by validation request id.
      description: Returns the analytic validation status (one of 'queued,' 'processing,'
        or 'completed' and the result from running the analytic (when status is 'completed').
      operationId: retrieveAnalyticValidationResult
      x-api-path-slug: apiv1cataloganalyticsidvalidationvalidationrequestid-get
      parameters:
      - in: path
        name: id
        description: analytic id
      - in: path
        name: validationRequestId
        description: analytic validation request id
      responses:
        2:
          description: Successful response
      tags:
      - Analytic
      - Validation
      - Status
      - By
      - Validation
      - Request
      - Id
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
swagger: "2.0"
x-collection-name: Open Bank Project
x-complete: 1
info:
  title: Account and Transaction API Specification
  description: swagger-for-account-and-transaction-api-specification
  termsOfService: https://www.openbanking.org.uk/terms
  contact:
    name: Service Desk
    email: ServiceDesk@openbanking.org.uk
  version: 1.0.0
basePath: /open-banking/v2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account-requests/{AccountRequestId}:
    get:
      summary: Get an account request
      description: Get an account request
      operationId: GetAccountRequest
      x-api-path-slug: accountrequestsaccountrequestid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Banking
      - Banks
      - Account
      - Request
    delete:
      summary: Delete an account request
      description: Delete an account request
      operationId: DeleteAccountRequest
      x-api-path-slug: accountrequestsaccountrequestid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Banking
      - Banks
      - Account
      - Request
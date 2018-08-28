---
swagger: "2.0"
x-collection-name: Postmark
x-complete: 0
info:
  title: Postmark Account Request a new DKIM Key
  description: "Requests a new DKIM key to be created. Until the DNS entries are confirmed,
    \nthe new values will be in the `DKIMPendingHost` and `DKIMPendingTextValue` fields.
    \nAfter the new DKIM value is verified in DNS, the pending values will migrate
    to \n`DKIMTextValue` and `DKIMPendingTextValue` and Postmark will begin to sign
    emails \nwith the new DKIM key."
  version: 0.9.0
host: api.postmarkapp.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /senders/{signatureid}/requestnewdkim:
    post:
      summary: Request a new DKIM Key
      description: "Requests a new DKIM key to be created. Until the DNS entries are
        confirmed, \nthe new values will be in the `DKIMPendingHost` and `DKIMPendingTextValue`
        fields. \nAfter the new DKIM value is verified in DNS, the pending values
        will migrate to \n`DKIMTextValue` and `DKIMPendingTextValue` and Postmark
        will begin to sign emails \nwith the new DKIM key."
      operationId: requestNewDKIMKeyForSenderSignature
      x-api-path-slug: senderssignatureidrequestnewdkim-post
      parameters:
      - in: path
        name: signatureid
        description: The ID for the Sender Signature for which a new DKIM Key should
          be generated
      - in: header
        name: X-Postmark-Account-Token
        description: The token associated with the Account on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Senders
      - Signatureid
      - Requestnewdkim
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
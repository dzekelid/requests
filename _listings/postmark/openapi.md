swagger: "2.0"
x-collection-name: Postmark
x-complete: 1
info:
  title: Postmark Account-level
  description: postmark-makes-sending-and-receiving-email-incredibly-easy--the-accountlevel-api-allows-users-toconfigure-all-servers-domains-and-sender-signatures-associated-with-an-account-
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
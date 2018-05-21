---
name: SendGrid
x-slug: sendgrid
description: SendGrid is a cloud-based email service that delivers email on behalf
  of companies to increase deliverability and improve customer communications integration
  with new or existing email systems is done via SMTP or through a REST API, providing
  metrics on outgoing email, and handles unsubscribe links, abiding by anti-spam regulations.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Requests
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid Get Scopes Requests
  x-api-slug: sendgrid
  description: |-
    This endpoint allows you to retrieve a list of all recent access requests.

    **Note:** The Response Header's 'link' parameter will include pagination info. For example:

    link: ```<https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="first"; title="1", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=10>; rel="last"; title="2", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="prev"; title="1"```
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//scopes/requests
  tags: Email,Scopes, Requests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/scopesrequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/scopesrequests-get-openapi.md
- name: SendGrid Delete Scopes Requests Request
  x-api-slug: sendgrid
  description: |-
    This endpoint allows you to deny an attempt to access your account.

    **Note:** Only teammate admins may delete a teammate's access request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//scopes/requests/{request_id}
  tags: Email,Scopes, Requests, Request
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/scopesrequestsrequest-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/scopesrequestsrequest-id-delete-openapi.md
- name: SendGrid Patch Scopes Requests Request  Approve
  x-api-slug: sendgrid
  description: "This endpoint allows you to approve an access attempt.\n\n**Note:**
    Only teammate admins may approve another teammate\u2019s access request."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//scopes/requests/{request_id}/approve
  tags: Email,Scopes, Requests, Request, , Approve
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/scopesrequestsrequest-idapprove-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/scopesrequestsrequest-idapprove-patch-openapi.md
- name: SendGrid
  x-api-slug: sendgrid
  description: SendGrids cloud-based email infrastructure relieves businesses of the
    cost and complexity of maintaining custom email systems. SendGrid provides reliable
    delivery, scalability and real-time analytics along with flexible APIs that make
    custom integration a breeze.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3
  tags: Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/sendgrid/openapi.md
x-common:
- type: x-net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-nodejs-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
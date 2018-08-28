---
name: PayJunction
x-slug: payjunction
description: PayJunction is a Level 1 PCI Compliant Service Provider that services
  thousands of businesses in every state in the United States. Since 2000, PayJunction
  has rapidly become a leading developer and provider of cutting edge merchant technology.
  PayJunction has also formed strategic alliances with leading financial institutions
  and technology partners to deliver the most comprehensive services in the industry.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/payjunction-logo.png
x-kinRank: "9"
x-alexaRank: "147448"
tags: Requests
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/payjunction/apis.md
specificationVersion: "0.14"
apis:
- name: PayJunction API Basic - Get Smart Terminals Requests
  x-api-slug: smartterminalsrequestsrequestpaymentid-get
  description: "Gets the status of a Smart Terminal payment request by querying the
    requestPaymentId returned by POST /smartterminals/{smartterminalId}/request-payment\n\nThe
    status of a payment request can be queried up to 1 day after the Smart Terminal
    payment request has been completed. After this cut off the requestPaymentId is
    purged and will return a 404 Not Found when queried. \n\nIn order to discourage
    busy polling, requests to this endpoint are rate limited to 1 request every 2
    seconds per request."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/payjunction-logo.png
  humanURL: http://payjunction.com/
  baseURL: https://example.com//
  tags: Syndication, Commerce, Payments, Pos, Retail, Payments, Target, Credit, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/payjunction/smartterminalsrequestsrequestpaymentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/payjunction/smartterminalsrequestsrequestpaymentid-get-openapi.md
x-common:
- type: x-postman-collection
  url: https://developer.payjunction.com/hc/article_attachments/360005001354/PayJunction%20API%20Basic.postman_collection.json
- type: x-api-gallery
  url: http://paretonetwork.api.gallery.streamdata.io
- type: x-api-stack
  url: http://payjunction.stack.network
- type: x-base
  url: https://api.payjunction.com
- type: x-blog
  url: http://www.pathable.com/category/blog/
- type: x-blog-rss
  url: http://blog.pathable.com/feeds/posts/default?alt=rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/payjunction
- type: x-developer
  url: http://developer.payjunction.com/
- type: x-github
  url: https://github.com/PayJunction
- type: x-twitter
  url: https://twitter.com/PayJunction
- type: x-website
  url: http://payjunction.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
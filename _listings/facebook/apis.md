---
name: Facebook
x-slug: facebook
description: Facebook is an online social networking service that allows its users
  to connect with friends and family as well as make new connections. It provides
  its users with the ability to create a profile, update information, add images,
  send friend requests, and accept requests from other users. Its features include
  status update, photo tagging and sharing, and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/facebook_2015_logo_detail.png
x-kinRank: "9"
x-alexaRank: ""
tags: Requests
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/apis.md
specificationVersion: "0.14"
apis:
- name: Facebook Get User Apprequests
  x-api-slug: facebook
  description: User Apprequests
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/facebook_2015_logo_detail.png
  humanURL: https://facebook.com
  baseURL: https://graph.facebook.com//v3.0//&#123;user-id&#125;/apprequests
  tags: User,Apprequests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/123userid125apprequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/123userid125apprequests-get-openapi.md
- name: Facebook Get User Favorite Requests
  x-api-slug: facebook
  description: User Favorite Requests
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/facebook_2015_logo_detail.png
  humanURL: https://facebook.com
  baseURL: https://graph.facebook.com//v3.0//&#123;user-id&#125;/favorite_requests
  tags: User,Favorite,Requests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/123userid125favorite-requests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/123userid125favorite-requests-get-openapi.md
- name: Facebook Get Me Friendrequests
  x-api-slug: facebook
  description: A person&#039;s pending friend requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/facebook_2015_logo_detail.png
  humanURL: https://facebook.com
  baseURL: https://graph.facebook.com//v3.0//me/friendrequests
  tags: Me,Friendrequests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/mefriendrequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/mefriendrequests-get-openapi.md
- name: Facebook
  x-api-slug: facebook
  description: Facebook is an online social networking service that allows its users
    to connect with friends and family as well as make new connections. It provides
    its users with the ability to create a profile, update information, add images,
    send friend requests, and accept requests from other users. Its features include
    status update, photo tagging and sharing, and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/facebook_2015_logo_detail.png
  humanURL: https://facebook.com
  baseURL: https://graph.facebook.com//v3.0
  tags: Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/facebook/openapi.md
x-common:
- type: x-android-sdk
  url: https://developers.facebook.com/docs/android/share
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/facebook/apidescription?format=internal&ver=1386216190000
- type: x-application-gallery
  url: https://developers.facebook.com/docs/showcase/
- type: x-base
  url: https://graph.facebook.com
- type: x-best-practices
  url: https://developers.facebook.com/docs/sharing/best-practices
- type: x-blog
  url: http://blog.facebook.com
- type: x-blog-rss
  url: https://www.facebook.com/business/news/rss/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/facebook
- type: x-developer
  url: https://developers.facebook.com/
- type: x-forum
  url: https://www.facebook.com/groups/fbdevelopers
- type: x-github
  url: https://github.com/facebook
- type: x-ios-sdk
  url: https://developers.facebook.com/docs/ios/share
- type: x-issues
  url: https://developers.facebook.com/status/issues/
- type: x-javascript-library
  url: https://developers.facebook.com/docs/reference/javascript/
- type: x-partners
  url: https://facebookmarketingpartners.com/
- type: x-php-sdk
  url: https://developers.facebook.com/docs/reference/php/
- type: x-plugins
  url: https://developers.facebook.com/docs/plugins/
- type: x-privacy
  url: https://www.facebook.com/settings?tab=privacy
- type: x-road-map
  url: https://developers.facebook.com/docs/apps/migrations
- type: x-status
  url: https://developers.facebook.com/status/
- type: x-terms-of-service
  url: https://www.facebook.com/terms
- type: x-terms-of-service
  url: https://developers.facebook.com/policy
- type: x-transparency-report
  url: https://www.facebook.com/about/government_requests
- type: x-twitter
  url: https://twitter.com/facebook
- type: x-website
  url: https://facebook.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
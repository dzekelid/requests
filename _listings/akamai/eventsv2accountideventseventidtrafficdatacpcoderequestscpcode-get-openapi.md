---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Get Event&#8217;s Requests per CP Code
  description: Get Event&#8217;s Requests per CP Code
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/requests/{cpcode}:
    get:
      summary: Get Event&#8217;s Edge Requests, per CP Code
      description: Get Event&#8217;s Edge Requests, per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeedgerequestscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeedgerequestscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Edge
      - Requests
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/requests:
    get:
      summary: Get Event&#8217;s Origin Requests
      description: Get Event&#8217;s Origin Requests
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginrequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginrequests-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Requests
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/requests/{cpcode}:
    get:
      summary: Get Event&#8217;s Origin Requests per CP Code
      description: Get Event&#8217;s Origin Requests per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginrequestscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginrequestscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Requests
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/requests:
    get:
      summary: Get Event&#8217;s Requests
      description: Get Event&#8217;s Requests
      operationId: eventsv2accountideventseventidtrafficdatacpcoderequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcoderequests-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Requests
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/requests/{cpcode}:
    get:
      summary: Get Event&#8217;s Requests per CP Code
      description: Get Event&#8217;s Requests per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcoderequestscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcoderequestscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Requests
      - Cpcode
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
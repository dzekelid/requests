---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
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
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressrequests:
    get:
      summary: Get Request Data for Flash Live Streams
      description: Get Request Data for Flash Live Streams
      operationId: eventsv2accountideventseventidtrafficdataflegressrequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressrequests-get
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
      - Fl
      - Egressrequests
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressrequests/{streamId}:
    get:
      summary: Get Request Data for a Flash Live Stream
      description: Get Request Data for a Flash Live Stream
      operationId: eventsv2accountideventseventidtrafficdataflegressrequestsstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressrequestsstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
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
      - Fl
      - Egressrequests
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressrequests:
    get:
      summary: Get Request Data for Silverlight Live Streams
      description: Get Request Data for Silverlight Live Streams
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressrequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressrequests-get
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
      - Hdsll
      - Egressrequests
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressrequests/{streamId}:
    get:
      summary: Get Request Data for a Silverlight Live Stream
      description: Get Request Data for a Silverlight Live Stream
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressrequestsstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressrequestsstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
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
      - Hdsll
      - Egressrequests
      - Stream
  /config-secure-provisioning-service/v1/sps-requests:
    post:
      summary: Create a Request
      description: Create a Request
      operationId: configsecureprovisioningservicev1spsrequestscontractidgroupidafterinformation
      x-api-path-slug: configsecureprovisioningservicev1spsrequests-post
      parameters:
      - in: query
        name: after
        description: If specified for GET requests, returns only the SPS requests
          created after the date entered
        type: string
      - in: query
        name: contractId
        description: For POST requests, the ID of the contract associated with the
          new policy
        type: string
      - in: query
        name: groupId
        description: For POST requests, the ID of the group associated with the new
          policy
        type: string
      - in: query
        name: information
        description: If specified for GET requests, returns parameters posted with
          the SPS request resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Secure
      - Provisioning
      - Service
      - Sps
      - Requests
      - Contract
      - group
      - after
      - information
    get:
      summary: List SPS Requests
      description: List SPS Requests
      operationId: configsecureprovisioningservicev1spsrequestscontractidgroupidafterinformation
      x-api-path-slug: configsecureprovisioningservicev1spsrequests-get
      parameters:
      - in: query
        name: after
        description: If specified for GET requests, returns only the SPS requests
          created after the date entered
        type: string
      - in: query
        name: contractId
        description: For POST requests, the ID of the contract associated with the
          new policy
        type: string
      - in: query
        name: groupId
        description: For POST requests, the ID of the group associated with the new
          policy
        type: string
      - in: query
        name: information
        description: If specified for GET requests, returns parameters posted with
          the SPS request resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Secure
      - Provisioning
      - Service
      - Sps
      - Requests
      - Contract
      - group
      - after
      - information
---
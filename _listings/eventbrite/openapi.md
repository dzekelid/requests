swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 1
info:
  title: Eventbrite
  description: create-manage--promote-events--add-eventmanagement-features-to-your-site--show-the-world-what-exciting-things-are-happening-around-them-
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /refund_requests/{id}/:
    get:
      summary: Get Refund Requests
      description: Gets a refund-request for the specified refund request.
      operationId: getRefundRequests
      x-api-path-slug: refund-requestsid-get
      responses:
        200:
          description: OK
      tags:
      - Refund
      - Requests
    post:
      summary: Post Refund Requests
      description: Update a refund-request for a specific order. Each element in items
        is a refund-item
      operationId: postRefundRequests
      x-api-path-slug: refund-requestsid-post
      parameters:
      - in: query
        name: from_email
        description: The email of the person is making the request
        type: query
      - in: query
        name: from_name
        description: The name of the person is making the request
        type: query
      - in: query
        name: items
        description: 'A list of items formatted as: [{&#8220;order_id&#8221;: &#8220;123&#8221;},'
        type: query
      - in: query
        name: message
        description: The Message of the request
        type: query
      - in: query
        name: reason
        description: 'The reason of the request (Valid choices are: duplicate_order,
          event_cancelled, event_not_as_described, no_longer_able_to_attend, event_postponed,
          request_not_within_event_refund_policy, request_inaccurate, refunded_offline,
          or alternate_resolution_offered)'
        type: query
      responses:
        200:
          description: OK
      tags:
      - Refund
      - Requests
  /refund_requests/:
    post:
      summary: Post Refund Requests
      description: Creates a refund-request for a specific order. Each element in
        items is a refund-item
      operationId: postRefundRequests
      x-api-path-slug: refund-requests-post
      parameters:
      - in: query
        name: from_email
        description: The email of the person is making the request
        type: query
      - in: query
        name: from_name
        description: The name of the person is making the request
        type: query
      - in: query
        name: items
        description: 'A list of items formatted as: [{&#8220;order_id&#8221;: &#8220;123&#8221;},'
        type: query
      - in: query
        name: message
        description: The Message of the request
        type: query
      - in: query
        name: reason
        description: 'The reason of the request (Valid choices are: duplicate_order,
          event_cancelled, event_not_as_described, no_longer_able_to_attend, event_postponed,
          request_not_within_event_refund_policy, request_inaccurate, refunded_offline,
          or alternate_resolution_offered)'
        type: query
      responses:
        200:
          description: OK
      tags:
      - Refund
      - Requests
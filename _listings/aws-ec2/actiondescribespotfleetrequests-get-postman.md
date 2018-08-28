{
  "info": {
    "name": "AWS EC2 API Describe Spot Fleet Requests",
    "_postman_id": "af1e2bb2-8771-4aa3-a15d-f37eb026de1f",
    "description": "Describes your Spot fleet requests.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Spot Instance Requests",
      "item": [
        {
          "id": "5e3497db-e1ce-47fe-ae21-c155a361d404",
          "name": "describespotinstancerequests",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotInstanceRequests?AvailabilityZone=AvailabilityZone&DryRun=DryRun&EndTime=EndTime&Filter.N=Filter.N&InstanceType.N=InstanceType.N&MaxResults=MaxResults&NextToken=NextToken&ProductDescription.N=ProductDescription.N&StartTime=StartTime",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Spot instance requests that belong to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9f9edc9-93e9-409c-b51f-980178a72f2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Sport Fleet Requests",
      "item": [
        {
          "id": "ca74f19f-96fc-400c-b058-29df84dccc85",
          "name": "describespotfleetrequests",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotFleetRequests",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your Spot fleet requests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "807225f1-2ef0-41fb-b21a-8d37a773f05e"
            }
          ]
        }
      ]
    }
  ]
}
---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Bulk Publish
  version: 1.0.0
  description: Initiates a bulk publish of all existing datasets for an Identity Pool
    to the configured stream.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BulkPublish:
    get:
      summary: Bulk Publish
      description: Initiates a bulk publish of all existing datasets for an Identity
        Pool to the configured stream.
      operationId: bulkPublish
      x-api-path-slug: actionbulkpublish-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Publish
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
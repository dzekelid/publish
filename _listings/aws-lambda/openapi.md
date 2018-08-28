swagger: "2.0"
x-collection-name: AWS Lambda
x-complete: 1
info:
  title: AWS Lambda API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PublishVersion:
    get:
      summary: Publish Version
      description: Publishes a version of your function from the current snapshot
        of $LATEST.
      operationId: publishVersion
      x-api-path-slug: actionpublishversion-get
      parameters:
      - in: query
        name: FunctionName
        description: The Lambda function name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Version
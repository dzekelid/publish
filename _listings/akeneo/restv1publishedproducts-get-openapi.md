---
swagger: "2.0"
x-collection-name: Akeneo
x-complete: 0
info:
  title: Akeneo PIM API published products (2.x and EE only)
  description: Published products (2.x and ee only).
  version: 1.0.0
host: example.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/v1/published-products/13527420:
    get:
      summary: published product (2.x and EE only)
      description: Assuming that the given identifier is the identifier of an existing
        product that is currently published
      operationId: RestV1PublishedProducts13527420Get
      x-api-path-slug: restv1publishedproducts13527420-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Published
      - Product
      - (2
      - X
      - EE
      - Only)
  /rest/v1/published-products:
    get:
      summary: published products (2.x and EE only)
      description: Published products (2.x and ee only).
      operationId: RestV1PublishedProductsGet
      x-api-path-slug: restv1publishedproducts-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Published
      - Products
      - (2
      - X
      - EE
      - Only)
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
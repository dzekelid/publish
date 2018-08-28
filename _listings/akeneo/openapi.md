swagger: "2.0"
x-collection-name: Akeneo
x-complete: 1
info:
  title: Official Akeneo PIM API
  description: the-akeneo-api-brought-to-youfind-out-how-this-postman-collection-works-by-visiting-httpapi-akeneo-com
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
---
swagger: "2.0"
x-collection-name: Google Tag Manager
x-complete: 1
info:
  title: Tag Manager
  description: accesses-tag-manager-accounts-and-containers-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /tagmanager/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{accountId}/containers/{containerId}/versions/{containerVersionId}/publish:
    post:
      summary: Publish Container Version
      description: Publishes a Container Version.
      operationId: tagmanager.accounts.containers.versions.publish
      x-api-path-slug: accountsaccountidcontainerscontaineridversionscontainerversionidpublish-post
      parameters:
      - in: path
        name: accountId
        description: The GTM Account ID
      - in: path
        name: containerId
        description: The GTM Container ID
      - in: path
        name: containerVersionId
        description: The GTM Container Version ID
      - in: query
        name: fingerprint
        description: When provided, this fingerprint must match the fingerprint of
          the container version in storage
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Versions
---
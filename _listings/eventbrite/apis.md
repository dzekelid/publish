---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite brings people together through live experiences. Discover
  events that match your passions, or create your own with online ticketing tools.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
x-kinRank: "9"
x-alexaRank: "643"
tags: Publish
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/publish/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite - Post Events Publish
  x-api-slug: eventsidpublish-post
  description: |-
    Publishes an event if it has not already been deleted. In order for publish to be permitted, the event must have all
    necessary information, including a name and description, an organizer, at least one ticket, and valid payment options.
    This API endpoint will return argument errors for event fields that fail to validate the publish requirements. Returns
    a boolean indicating success or failure of the publish.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/publish/master/_listings/eventbrite/eventsidpublish-post-openapi.md
- name: Eventbrite - Post Series Publish
  x-api-slug: seriesidpublish-post
  description: |-
    Publishes a repeating event series and all of its occurrences that are not already canceled or deleted. Once a date is cancelled it can still be uncancelled and can be viewed by the public. A deleted date cannot be undeleted and cannot by viewed by the public. In order for
    publish to be permitted, the event must have all necessary information, including a name and description, an organizer,
    at least one ticket, and valid payment options. This API endpoint will return argument errors for event fields that
    fail to validate the publish requirements. Returns a boolean indicating success or failure of the publish.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/publish/master/_listings/eventbrite/seriesidpublish-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/publish/master/_listings/eventbrite/seriesidpublish-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://europeana.api.gallery.streamdata.io
- type: x-api-stack
  url: http://eventbrite.stack.network
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/eventbrite/apidescription?format=internal&ver=1351170233000
- type: x-authentication
  url: https://developer.eventbrite.com/docs/auth/
- type: x-base
  url: https://www.eventbriteapi.com/
- type: x-blog
  url: http://blog.eventbrite.com/
- type: x-blog-rss
  url: http://blog.eventbrite.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/eventbrite
- type: x-crunchbase
  url: https://crunchbase.com/organization/eventbrite
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdks-io
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-twitter
  url: https://twitter.com/eventbrite
- type: x-website
  url: http://eventbriteapi.com
- type: x-website
  url: http://developer.eventbrite.com/
- type: x-website
  url: http://eventbrite.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
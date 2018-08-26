---
name: Spire Global
x-slug: spire-global
description: Spire Global, Inc. is an American private company specializing in data
  gathered from a network of small satellites.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spire-logo.png
x-kinRank: "7"
x-alexaRank: "557670"
tags: Vessels
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vessels/master/_listings/spire-global/apis.md
specificationVersion: "0.14"
apis:
- name: Spire API - Find Vessels Arriving Between Date/Time Window
  x-api-slug: vessels-get
  description: |-
    Returns all vessels with an ETA greater than the `arriving_after` and ETA less than the `arriving_before` parameter.

    Query can also be used without the `arriving_before` parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spire-logo.png
  humanURL: https://spire.com
  baseURL: https://ais.spire.com//
  tags: Satellites, SaaS, Enterprise, Technology, Marine, Weather, Aviation, Shipping,
    General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vessels/master/_listings/spire-global/vessels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vessels/master/_listings/spire-global/vessels-get-openapi.md
- name: Spire API - Get Individual Vessel
  x-api-slug: vesselsa5b738b4faf04a7e9a871c0ccfb123d2-get
  description: Returns individual ship details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/spire-logo.png
  humanURL: https://spire.com
  baseURL: https://ais.spire.com//
  tags: Satellites, SaaS, Enterprise, Technology, Marine, Weather, Aviation, Shipping,
    General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vessels/master/_listings/spire-global/vesselsa5b738b4faf04a7e9a871c0ccfb123d2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vessels/master/_listings/spire-global/vesselsa5b738b4faf04a7e9a871c0ccfb123d2-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://spectrocoin.api.gallery.streamdata.io
- type: x-api-stack
  url: http://spire.global.stack.network
- type: x-blog
  url: https://spire.com/insights/
- type: x-crunchbase
  url: https://crunchbase.com/organization/nanosatisfi
- type: x-developer
  url: https://spire.com/contact/developer-portal/
- type: x-email
  url: legal@spire.com
- type: x-twitter
  url: https://twitter.com/SpireGlobal
- type: x-website
  url: https://spire.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
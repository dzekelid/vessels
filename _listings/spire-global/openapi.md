swagger: "2.0"
x-collection-name: Spire Global
x-complete: 1
info:
  title: Spire API
  description: todo-add-description
  version: 1.0.0
host: ais.spire.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /vessels:
    get:
      summary: Find Vessels Arriving Between Date/Time Window
      description: |-
        Returns all vessels with an ETA greater than the `arriving_after` and ETA less than the `arriving_before` parameter.

        Query can also be used without the `arriving_before` parameter.
      operationId: VesselsGet10
      x-api-path-slug: vessels-get
      parameters:
      - in: query
        name: arriving_after
      - in: query
        name: arriving_before
      responses:
        200:
          description: OK
      tags:
      - Vessels
  /vessels/a5b738b4-faf0-4a7e-9a87-1c0ccfb123d2:
    get:
      summary: Get Individual Vessel
      description: Returns individual ship details.
      operationId: VesselsA5b738b4Faf04a7e9a871c0ccfb123d2Get
      x-api-path-slug: vesselsa5b738b4faf04a7e9a871c0ccfb123d2-get
      responses:
        200:
          description: OK
      tags:
      - Vessels
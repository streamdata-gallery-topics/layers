---
swagger: "2.0"
x-collection-name: NxtPort
x-complete: 0
info:
  title: NxtPort Bel Air API Retrieve available layers
  description: "This operation lists the currently available city layers. \nThe returned
    strings can then be used as a layerId path parameter in the /layers operations
    included in this API."
  termsOfService: https://www.nxtport.eu/General-Terms-And-Conditions
  version: 1.0.0
host: api-stg.nxtport.eu
basePath: /belair/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /layers:
    get:
      summary: Retrieve available layers
      description: "This operation lists the currently available city layers. \nThe
        returned strings can then be used as a layerId path parameter in the /layers
        operations included in this API."
      operationId: getLayers
      x-api-path-slug: layers-get
      responses:
        200:
          description: OK
      tags:
      - Layers
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
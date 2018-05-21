---
swagger: "2.0"
x-collection-name: Clearbit
x-complete: 0
info:
  title: Clearbit Person Retrieves a person and company by email address
  description: Retrieves a person and company by email address.
  version: v1
host: person.clearbit.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /combined/find:
    get:
      summary: Retrieves a person and company by email address
      description: Retrieves a person and company by email address.
      operationId: getCombined
      x-api-path-slug: combinedfind-get
      parameters:
      - in: query
        name: email
        description: the persons email address
      responses:
        200:
          description: OK
      tags:
      - People
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
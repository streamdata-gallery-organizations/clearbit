---
swagger: "2.0"
x-collection-name: Clearbit
x-complete: 0
info:
  title: Clearbit Company Logo Get Logo
  description: Gets a logo for the requested domain.
  termsOfService: The API is incredibly simple, taking a companyu2019s domain and
    returning an image.
  contact:
    name: Clearbit
    url: https://dashboard.clearbit.com/support
    email: support@clearbit.com
  version: 1.0.0
host: logo.clearbit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '{domain}':
    get:
      summary: Get Logo
      description: Gets a logo for the requested domain.
      operationId: getLogo
      x-api-path-slug: domain-get
      parameters:
      - in: path
        name: domain
        description: the domain the url is being requested for
      - in: query
        name: format
        description: Format of the default - either png or jpg
      - in: query
        name: greyscale
        description: Enables greyscaling
      - in: query
        name: size
        description: Size of the image returned
      responses:
        200:
          description: OK
      tags:
      - Company
      - Logos
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
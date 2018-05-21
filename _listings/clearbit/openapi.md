---
swagger: "2.0"
x-collection-name: Clearbit
x-complete: 1
info:
  title: Clearbit Person
  description: the-clearbit-api-for-person
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
---
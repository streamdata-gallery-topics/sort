---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Post Users Assortment
  description: |-
    Set a user&#8217;s assortment and returns the assortment for the specified
    user.
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id}/assortment/:
    get:
      summary: Get Users Assortment
      description: Retrieve the assortment for the user.
      operationId: getUsersAssortment
      x-api-path-slug: usersidassortment-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Assortment
    post:
      summary: Post Users Assortment
      description: |-
        Set a user&#8217;s assortment and returns the assortment for the specified
        user.
      operationId: postUsersAssortment
      x-api-path-slug: usersidassortment-post
      parameters:
      - in: query
        name: plan
        description: The assortments package to upgrade/downgrade to
        type: query
      responses:
        200:
          description: OK
      tags:
      - Users
      - Assortment
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
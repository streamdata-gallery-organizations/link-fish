---
swagger: "2.0"
x-collection-name: link.fish
x-complete: 0
info:
  title: link.fish Get mobile apps
  description: |-
    Visits the URL and checks if there are mobile apps on them and returns the found ones.

    Will by default return the app identifiers and not the full URL to the apps. To return URLs instead set the parameter "return_urls" to true.

    The URLs can also be created manually like this:

    | Property | URL                                                |
    | -------- | -------------------------------------------------- |
    | android  | https://play.google.com/store/apps/details?id={ID} |
    | ios      | https://itunes.apple.com/us/app/app-name/id{ID}    |

    Properties only get set when a value for it has been found. That means that if no app has been found only the property "url" will be set.
  termsOfService: https://link.fish/terms-of-service/
  contact:
    name: link.fish
    url: https://link.fish/api
    email: api@link.fish
  version: "2017-12-01"
host: api.link.fish
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Urls/apps:
    get:
      summary: Get mobile apps
      description: |-
        Visits the URL and checks if there are mobile apps on them and returns the found ones.

        Will by default return the app identifiers and not the full URL to the apps. To return URLs instead set the parameter "return_urls" to true.

        The URLs can also be created manually like this:

        | Property | URL                                                |
        | -------- | -------------------------------------------------- |
        | android  | https://play.google.com/store/apps/details?id={ID} |
        | ios      | https://itunes.apple.com/us/app/app-name/id{ID}    |

        Properties only get set when a value for it has been found. That means that if no app has been found only the property "url" will be set.
      operationId: Urls.apps.get
      x-api-path-slug: urlsapps-get
      parameters:
      - in: query
        name: browser_render
        description: If the page should be fully rendered with a browser to extract
          data
      - in: query
        name: return_urls
        description: Returns app URLs instead of the identifiers
      - in: query
        name: url
        description: The URL of the website to query
      responses:
        200:
          description: OK
      tags:
      - Urls
      - Apps
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
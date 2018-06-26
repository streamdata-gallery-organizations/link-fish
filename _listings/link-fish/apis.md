---
name: link.fish
x-slug: link-fish
description: Automatically get the information of the websites you are interested
  in and work with it together with others in real-time. Depending on the page you
  bookmark link.fish automatically extracts the data you actually care about. No matter
  if bedrooms for apartments, rating of movies or the cook time of your favorite recipe.
  Invite other people to your collection to work with them or make it public for everbody
  to see. All changes made will immediately be visible by everyone.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: link.fish
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/apis.md
specificationVersion: "0.14"
apis:
- name: link.fish Get mobile apps
  x-api-slug: link-fish
  description: |-
    Visits the URL and checks if there are mobile apps on them and returns the found ones.

    Will by default return the app identifiers and not the full URL to the apps. To return URLs instead set the parameter "return_urls" to true.

    The URLs can also be created manually like this:

    | Property | URL                                                |
    | -------- | -------------------------------------------------- |
    | android  | https://play.google.com/store/apps/details?id={ID} |
    | ios      | https://itunes.apple.com/us/app/app-name/id{ID}    |

    Properties only get set when a value for it has been found. That means that if no app has been found only the property "url" will be set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish////Urls/apps
  tags: Urls,Apps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsapps-get-openapi.md
- name: link.fish Extract data (browser)
  x-api-slug: link-fish
  description: Visits the URL with a full browser and extracts the data. This request
    costs 5 credits.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish////Urls/browser-data
  tags: Urls,Browser,Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsbrowserdata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsbrowserdata-get-openapi.md
- name: link.fish Generate screenshot (browser)
  x-api-slug: link-fish
  description: Visits the URL with full browser and creates a screenshot. This request
    costs 5 credits.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish////Urls/browser-screenshot
  tags: Urls,Browser,Screenshot
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsbrowserscreenshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsbrowserscreenshot-get-openapi.md
- name: link.fish Extract data
  x-api-slug: link-fish
  description: Visits the URL and extracts the data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish////Urls/data
  tags: Urls,Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsdata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsdata-get-openapi.md
- name: link.fish Get geo coordinates
  x-api-slug: link-fish
  description: |-
    Visits the URL and checks if there are Geo Coordinates on them and returns the found ones.

    Properties only get set when a value for both latitude and longitude have been found. That means that if no geo coordinates have been found only the property "url" will be set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish////Urls/geo-coordinates
  tags: Urls,Geo,Coordinates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsgeocoordinates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlsgeocoordinates-get-openapi.md
- name: link.fish Get social media accounts
  x-api-slug: link-fish
  description: |-
    Visits the URL and checks if there are any social media accounts and returns the found ones.

    Will by default return the account identifiers and not the full URL to the profiles. To return URLs instead set the parameter "return_urls" to true.

    The URLs can also be created manually like this:

    | Property        | URL                                    |
    | --------------- | -------------------------------------- |
    | facebookPage    | https://facebook.com/{ID}              |
    | githubUser      | https://github.com/{ID}                |
    | googlePlus      | https://plus.google.com/+{ID}          |
    | instagram       | https://instagram.com/{ID}             |
    | linkedInCompany | https://linkedin.com/company/{ID}      |
    | pinterest       | https://pinterest.com/{ID}             |
    | twitter         | https://twitter.com/{ID}               |
    | youTubeUser     | https://youtube.com/user/{ID}          |

    Properties only get set when a value for it has been found. That means that if no social media account has been found only the property "url" will be set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish////Urls/social-media
  tags: Urls,Social,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlssocialmedia-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/urlssocialmedia-get-openapi.md
- name: link.fish
  x-api-slug: link-fish
  description: Automatically get the information of the websites you are interested
    in and work with it together with others in real-time. Depending on the page you
    bookmark link.fish automatically extracts the data you actually care about. No
    matter if bedrooms for apartments, rating of movies or the cook time of your favorite
    recipe. Invite other people to your collection to work with them or make it public
    for everbody to see. All changes made will immediately be visible by everyone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish//
  tags: link.fish
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/link-fish/master/_listings/link-fish/openapi.md
x-common:
- type: x-developer
  url: https://link.fish/api/
- type: x-github
  url: https://github.com/link-fish
- type: x-twitter
  url: https://twitter.com/linkfish_
- type: x-website
  url: http://link.fish
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
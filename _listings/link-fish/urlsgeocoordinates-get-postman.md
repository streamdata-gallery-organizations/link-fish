{
  "info": {
    "name": "link.fish Get geo coordinates",
    "_postman_id": "847e459c-72cc-428d-b289-af18501747d4",
    "description": "Visits the URL and checks if there are Geo Coordinates on them and returns the found ones.\n\nProperties only get set when a value for both latitude and longitude have been found. That means that if no geo coordinates have been found only the property \"url\" will be set.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Urls",
      "item": [
        {
          "id": "5242c148-6282-4deb-b1a5-bf07715960f2",
          "name": "Urls.apps.get",
          "request": {
            "url": "http://api.link.fish/Urls/apps?browser_render=%7B%7D&return_urls=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Visits the URL and checks if there are mobile apps on them and returns the found ones.\n\nWill by default return the app identifiers and not the full URL to the apps. To return URLs instead set the parameter \"return_urls\" to true.\n\nThe URLs can also be created manually like this:\n\n| Property | URL                                                |\n| -------- | -------------------------------------------------- |\n| android  | https://play.google.com/store/apps/details?id={ID} |\n| ios      | https://itunes.apple.com/us/app/app-name/id{ID}    |\n\nProperties only get set when a value for it has been found. That means that if no app has been found only the property \"url\" will be set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7def5a0-b6a6-48e6-9854-304ee307cafd"
            }
          ]
        },
        {
          "id": "fdb64dc4-a348-4f8c-a9e8-c0099d4e3837",
          "name": "Urls.browser_data.get",
          "request": {
            "url": "http://api.link.fish/Urls/browser-data?item_format=%7B%7D&screenshot=%7B%7D&screenshot_file_format=%7B%7D&screenshot_width=%7B%7D&simplify_special_types=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Visits the URL with a full browser and extracts the data. This request costs 5 credits."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00175a87-97cd-4e22-91bf-54ceac9057d9"
            }
          ]
        },
        {
          "id": "e10ea379-841d-4f40-b119-37e51815d1fd",
          "name": "Urls.browser_screenshot.get",
          "request": {
            "url": "http://api.link.fish/Urls/browser-screenshot?file_format=%7B%7D&type=%7B%7D&url=%7B%7D&width=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Visits the URL with full browser and creates a screenshot. This request costs 5 credits."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d00faae6-d0e5-4de5-9fc7-d67635cf1300"
            }
          ]
        },
        {
          "id": "8e2a74dc-2c5f-4535-989e-8d0b72c4ff7d",
          "name": "Urls.data.get",
          "request": {
            "url": "http://api.link.fish/Urls/data?browser_render=%7B%7D&item_format=%7B%7D&simplify_special_types=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Visits the URL and extracts the data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02ce7f80-1c34-4bfb-9f4a-703760b33ce1"
            }
          ]
        },
        {
          "id": "0fc1f1d6-f6bd-4fc9-ab6b-7ef508c693d3",
          "name": "Urls.geo_coordinates.get",
          "request": {
            "url": "http://api.link.fish/Urls/geo-coordinates?browser_render=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Visits the URL and checks if there are Geo Coordinates on them and returns the found ones.\n\nProperties only get set when a value for both latitude and longitude have been found. That means that if no geo coordinates have been found only the property \"url\" will be set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "390efffd-3e2c-49ca-bdd8-4996324d2455"
            }
          ]
        }
      ]
    }
  ]
}
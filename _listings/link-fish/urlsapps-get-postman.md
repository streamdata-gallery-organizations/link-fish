{
  "info": {
    "name": "link.fish Get mobile apps",
    "_postman_id": "fef18792-4d9f-4ce2-bb6f-658d8915d201",
    "description": "Visits the URL and checks if there are mobile apps on them and returns the found ones.\n\nWill by default return the app identifiers and not the full URL to the apps. To return URLs instead set the parameter \"return_urls\" to true.\n\nThe URLs can also be created manually like this:\n\n| Property | URL                                                |\n| -------- | -------------------------------------------------- |\n| android  | https://play.google.com/store/apps/details?id={ID} |\n| ios      | https://itunes.apple.com/us/app/app-name/id{ID}    |\n\nProperties only get set when a value for it has been found. That means that if no app has been found only the property \"url\" will be set.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Urls",
      "item": [
        {
          "id": "211cd37b-0082-4a41-9c3f-5931d75a7f39",
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
              "id": "fb35c997-96eb-4c2e-b7af-56b1b05d4538"
            }
          ]
        }
      ]
    }
  ]
}
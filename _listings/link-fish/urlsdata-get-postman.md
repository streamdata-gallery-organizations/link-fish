{
  "info": {
    "name": "link.fish Extract data",
    "_postman_id": "934f0af5-7ba5-4198-b0c0-fece69c65e1f",
    "description": "Visits the URL and extracts the data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Urls",
      "item": [
        {
          "id": "235e0187-1cfb-4f81-b438-9df37d2099c6",
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
              "id": "dbe40791-de72-465b-8f3f-de4b5976c46c"
            }
          ]
        },
        {
          "id": "c7f6cf27-f27b-4645-9135-472a0a9f7d92",
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
              "id": "b3106c82-b784-49e7-bf15-53537d32f1c4"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "link.fish Extract data (browser)",
    "_postman_id": "c3f23c03-8c25-415c-9f7a-385c188556b4",
    "description": "Visits the URL with a full browser and extracts the data. This request costs 5 credits.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Urls",
      "item": [
        {
          "id": "0a21e48e-380d-4bbc-8656-b1f10bd348ce",
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
              "id": "0813e2a2-cc06-4ecb-b653-7bbd2dca2fb8"
            }
          ]
        }
      ]
    }
  ]
}
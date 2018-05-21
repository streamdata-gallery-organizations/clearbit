{
  "info": {
    "name": "Clearbit Company Logo Get Logo",
    "_postman_id": "7ca1c179-265f-45e1-bd5a-f0b4955d99d4",
    "description": "Gets a logo for the requested domain.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Company",
      "item": [
        {
          "id": "b3f7f903-3ff9-4d1b-a731-02726fcf1bb9",
          "name": "getLogo",
          "request": {
            "url": {
              "protocol": "http",
              "host": "logo.clearbit.com",
              "path": [
                ":domain"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "greyscale",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "size",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a logo for the requested domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9cae40e-4307-4bb6-ae05-4e88fbde9e27"
            }
          ]
        }
      ]
    }
  ]
}
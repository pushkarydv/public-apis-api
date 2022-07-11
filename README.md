# <p align="center"> Public APIs api</p>

a list to 1400+ apis how they are used, their documentation, properties and a lot more all divided int 50+ cateogories all this data just a api call away 🚀

# How to use 🤔
we suggest using axios for this

## 🐛 Get Categories

this api endpoint gives you a list of categories APIs are available in

`https://public-apis-api.vercel.app/api/apis`

this will return you a name object contaning array of all API name and slug for that api details

example response

```js
{
  "name": [
    [
      "Animals",
      "animals"
    ],
    [
      "API 2",
      "slug_for_api_2"
    ]
  ]
}
```

## 🗯️ Get data by category

this api endpoint gives you a data by categories of API slug you provide ( slug can be obtained by previous endpoint as in upper example )

`https://public-apis-api.vercel.app/api/apis/slug_of_api`

this will return a `data` object contaning array of APIs

example query
`https://public-apis-api.vercel.app/api/apis/animals`

response:

```js
{
  "data": [
    [
      "API_name",
      "URL to api docs",
      "Api Description",
      "Auth",
      "https",
      "cors"
    ],
    [
      "AdoptAPet",
      "https://www.adoptapet.com/public/apis/pet_list.html",
      "Resource to help get pets adopted",
      "apiKey",
      "Yes",
      "Yes"
    ]
  ]
}
```

## Contribution

Everyone is Welcome to Contribute :)

## Contact

You can reach me on [Twitter @pushkaryadav\_](https://twitter.com/pushkaryadav_)

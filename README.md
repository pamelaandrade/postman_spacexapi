# Postman SpaceX API

## Links:

[SpaceX API](https://docs.spacexdata.com/)
[Postman](https://www.postman.com/)
[Newman](https://docs.spacexdata.com/)
[newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)

### Getting started:

#### Install dependencies:

`npm i newman`
`npm i newman-reporter-html`

#### Run Test:

`newman run collections/spacexapi.postman_collection.json -e environments/spacexapi.postman_environment.json --reporters cli,htmlextra --reporter-htmlextra-export report.html`
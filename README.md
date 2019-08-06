# Oryx CRM routes

> machine-readable, always up-to-date Oryx CRM REST API route specifications

The package will update itself using a daily cronjob running on Travis once the API will be live.

Used for oryx-sdk development purpose.

Allow us to be much more flexible.

## Usage as Node module

```js
const ROUTES = require("oryxcommerce/crm-api-routes")();
```

returns a valid OpenAPI document describing the provided API.

If you don’t need the full document, you can require a specific operation instead

```js
const GET_CONTACT = require("oryxcommerce/crm-api-routes/openapi/api.oryxcrm.com/operations/contact/get.json");
```

# i18n-country-code

> Translations for country names based on its ISO Alpha 3 country code.

##  Install

```sh
$ npm install --save i18n-country-code
```

## Usage

### Node.js

```js
const translations = require("i18n-country-code/locales/en.json");

const countryName = translations["USA"];
// United States
```

### Webpack

Use it with dynamic import.

```js
const locale = "en"

import(`i18n-country-code/locales/${locale}.json`)
  .then(translations => {
    const countryName = translations["USA"];
    // United States
  })
```

## License

MIT © [VTEX](https://www.vtex.com)
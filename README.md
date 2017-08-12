# codename-universe

> Universe bodies names parser for [Codename](https://github.com/khaosdoctor/Codename) (Standalone)

## Usage

Install the package using either `npm install codename-universe --save` or `yarn add codename-universe`.

Require it and use the function `parse`:

```js
const universe = require('codename-universe')

console.log(universe.parse('2.1.4').codenameText) // V2.1.4 - Canopus
```

For more information about the API, see [Codename](https://github.com/khaosdoctor/Codename) project, this parser only abstracts the `parse` function, returning an instance of the original Codename parser
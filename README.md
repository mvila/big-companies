# big-companies [![npm version](https://img.shields.io/npm/v/big-companies.svg)](https://www.npmjs.com/package/big-companies)

List of the biggest companies in the world.

For each company, the following information are provided:

- `name`
- `shortNames`
- `url`

The `shortNames` property can be used to restrict usernames in a registration form. That's why I created this module.

Source: [Fortune Global 500](http://fortune.com/global500/) (2015).

## Installation

```
npm install --save big-companies
```

## Example

```javascript
var bigCompanies = require('big-companies');

console.log(bigCompanies[0]);
```

Will output:

```javascript
{
  name: 'Walmart',
  shortNames: ['walmart'],
  url: 'http://www.walmart.com'
}
```

## License

MIT

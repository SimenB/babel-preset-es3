# babel-preset-es3
[![npm version][npm-image]][npm-url]

> Babel preset for two ES3 transforms `transform-es3-member-expression-literals` and `transform-es3-property-literals`

This presets adds the two transforms for ES2 syntax compatibility.

## Install
```sh
$ npm install --save-dev babel-preset-es3
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es3"]
}
```

### Via CLI

```sh
$ babel script.js --preset es3
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es3"]
});
```

[npm-url]: https://npmjs.org/package/babel-preset-es3
[npm-image]: https://img.shields.io/npm/v/babel-preset-es3.svg

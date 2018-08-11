# jest-mdx-loader

Jest transformer that wraps mdx-js/mx webpack loader

## Install

```
yarn add --dev @mizchi/jest-mdx-loader
```

## Usage

Install jest-mdx-loader and then add it to your jest.config.js under transform:

```js
/// jest.config.js

module.exports = {
  //...
  transform: {
    "^.+\\.jsx?$": "babel-jest",
    ".mdx?$": "jest-mdx-loader"
  }
  //...
};
```

## Licence

MIT © [Joseph Black](https://josephconradblack.com)

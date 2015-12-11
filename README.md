 babel-preset-bleeding

> Babel preset for all bleeding edge es2015 plugins @ stage 0 with react/jsx, version * with loose enabled.

## Install

[![NPM](https://nodei.co/npm/babel-preset-bleeding.png?mini=true)](https://www.npmjs.org/package/babel-preset-bleeding)

```sh
$ npm install --save-dev babel-preset-bleeding
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["bleeding"]
}
```

### Via CLI

```sh
$ babel script.js --preset bleeding
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["bleeding"]
});
```
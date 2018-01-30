# babel-preset-functionly

> Babel preset for [Functionly](https://www.npmjs.com/package/functionly) node projects.

## Install

```sh
$ npm install --save-dev babel-preset-functionly
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["functionly"]
}
```

### Via CLI

```sh
$ babel script.js --presets functionly
```

### Via Node API

```javascript
require('babel-core').transform('code', {
  presets: ['functionly'],
});
```
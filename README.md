# babel-preset-es2015-allow-top-level-this

> Babel preset for all es2015 plugins and allow top level this.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-allow-top-level-this
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-allow-top-level-this"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-allow-top-level-this 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-allow-top-level-this"]
});
```
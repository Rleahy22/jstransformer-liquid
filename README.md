# jstransformer-liquid

[Liquid for Node.js](https://github.com/sirlantis/liquid-node) support for [JSTransformers](http://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-liquid/master.svg)](https://travis-ci.org/jstransformers/jstransformer-liquid)
[![Coverage Status](https://img.shields.io/coveralls/jstransformers/jstransformer-liquid/master.svg)](https://coveralls.io/r/jstransformers/jstransformer-liquid?branch=master)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-liquid/master.svg)](http://david-dm.org/jstransformers/jstransformer-liquid)
[![NPM version](https://img.shields.io/npm/v/jstransformer-liquid.svg)](https://www.npmjs.org/package/jstransformer-liquid)

## Installation

    npm install jstransformer-liquid

## API

```js
var liquid = require('jstransformer')(require('jstransformer-liquid'))

liquid.render('Hello {{ name }}!', {
  name: 'World'
}).body
//=> 'Hello, World!'
```

## License

MIT

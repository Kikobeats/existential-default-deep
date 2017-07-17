# existential-default-deep

[![Greenkeeper badge](https://badges.greenkeeper.io/Kikobeats/existential-default-deep.svg)](https://greenkeeper.io/)

![Last version](https://img.shields.io/github/tag/Kikobeats/existential-default-deep.svg?style=flat-square)
[![Build Status](http://img.shields.io/travis/Kikobeats/existential-default-deep/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/existential-default-deep)
[![Dependency status](http://img.shields.io/david/Kikobeats/existential-default-deep.svg?style=flat-square)](https://david-dm.org/Kikobeats/existential-default-deep)
[![Dev Dependencies Status](http://img.shields.io/david/dev/Kikobeats/existential-default-deep.svg?style=flat-square)](https://david-dm.org/Kikobeats/existential-default-deep#info=devDependencies)
[![NPM Status](http://img.shields.io/npm/dm/existential-default-deep.svg?style=flat-square)](https://www.npmjs.org/package/existential-default-deep)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

> Deep version of [existential-default](https://github.com/Kikobeats/existential-default).

## Install

```bash
npm install existential-default-deep
```

If you want to use in the browser (powered by [Browserify](http://browserify.org/)):

```bash
bower install existential-default-deep --save
```

and later link in your HTML:

```html
<script src="bower_components/existential-default-deep/dist/existential-default-deep.js"></script>
```

## Usage

```js
var existsDefault = require('existential-default-deep');
var hello = null;
hello = existsDefault(hello, 'world');
console.log(hello);
// => 'world'
```

## Related

* [existential](https://github.com/Kikobeats/existential) – The missing existential operator for JavaScript.
* [existential-assign](existential-assign) – Check for the existential value of a variable/object. Assign one if the value doesn't exist.
* [existential-default](https://github.com/Kikobeats/existential-default) – Check for the existential value of a variable and assign a value by default. 
 
## License

MIT © [Kiko Beats](http://www.kikobeats.com)

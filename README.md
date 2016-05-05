# emojis-list

[![Dependency status](http://img.shields.io/david/Kikobeats/emojis-list.svg?style=flat-square)](https://david-dm.org/Kikobeats/emojis-list)
[![Dev Dependencies Status](http://img.shields.io/david/dev/Kikobeats/emojis-list.svg?style=flat-square)](https://david-dm.org/Kikobeats/emojis-list#info=devDependencies)
[![NPM Status](http://img.shields.io/npm/dm/emojis-list.svg?style=flat-square)](https://www.npmjs.org/package/emojis-list)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

> Complete list of standard Unicode codes that represent emojis.

The file content all shortcuts declared that you can use for invoke a emoji.

## Install

```bash
npm install emojis-list --save
```

If you want to use in the browser (powered by [Browserify](http://browserify.org/)):

```bash
bower install emojis-list --save
```

and later link in your HTML:

```html
<script src="bower_components/emojis-list/dist/emojis-list.js"></script>
```

## Usage
### node
```
var emojis = require('emojis-list');
console.log(emojis[0]);
// => 🀄
```

### webpack
If you use it in `webpack`, don't forget to install `json-loader` to load it

```
//add in webpack.config.js
{test: /\.json$/,  loader: 'json'}
```

## Related

* [emojis-unicode](https://github.com/Kikobeats/emojis-unicode) – Complete list of standard Unicode codes that represent emojis.
* [emojis-keywords](https://github.com/Kikobeats/emojis-keywords) – Complete list of am emoji shortcuts.
* [is-emoji-keyword](https://github.com/Kikobeats/is-emoji-keyword) – Check if a word is a emoji shortcut.
* [is-standard-emoji](https://github.com/kikobeats/is-standard-emoji) – Simply way to check if a emoji is a standard emoji.
* [trim-emoji](https://github.com/Kikobeats/trim-emoji) – Deletes ':' from the begin and the end of an emoji shortcut.

## License

MIT © [Kiko Beats](http://www.kikobeats.com)

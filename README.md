# px2rem-exclude

Based on [postcss-px2rem](https://www.npmjs.com/package/postcss-px2rem) added the exclude folder option.

[![Downloads][downloads-image]][downloads-url]

[downloads-url]: https://www.npmjs.com/package/px2rem-ui-exclude

## Useage

### .postcssrc.js
```javascript
module.exports = {
  'plugins': {
    'px2rem-ui-exclude': {
      remUnit: 75,
      exclude: /node_modules|folder_name/i
    }
  }
}
```

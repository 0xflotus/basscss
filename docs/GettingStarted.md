
# Getting Started

```
npm install basscss
```

## Alternative Installation

### CDN

*Or* use a link from [npmcdn.com](https://npmcdn.com/basscss/css/basscss.min.css).

### Bower

Although it’s not listed in the Bower registry, any GitHub repo can be installed with bower.

```
bower install basscss/basscss
```

## Usage with PostCSS

When using [PostCSS]() with the [postcss-import](https://github.com/postcss/postcss-import) plugin, import the Basscss module.

```css
@import 'basscss';
```

The precompiled source code for Basscss requires the following plugins:
- [postcss-import](https://github.com/postcss/postcss-import)
- [postcss-custom-media](https://github.com/postcss/postcss-custom-media)
- [postcss-custom-properties](https://github.com/postcss/postcss-custom-properties)
- [postcss-calc](https://github.com/postcss/postcss-calc)

Custom properties can be set after the import.

```css
@import 'basscss';

:root {
  --font-family: Roboto, sans-serif;
}
```

## Webpack

With [webpack](https://webpack.github.io) use [css-loader](https://github.com/webpack/css-loader) to import Basscss in JavaScript.

```js
import basscss from 'basscss/css/basscss.min.css'
```

The precompiled source code can be imported using [postcss-loader](https://github.com/postcss/postcss-loader).

```js
import basscss from 'basscss/src/basscss.css'
```


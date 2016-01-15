# css-image-rendering 0.0.6

Css module of single purpose classes for image rendering

#### Stats

192 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-image-rendering
```

#### With Git

```
git clone https://github.com/tachyons-css/css-image-rendering
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-image-rendering";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-image-rendering">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   IMAGE RENDERING
*/
.render-auto { image-rendering: auto; }
.render-auto { image-rendering: crisp-edges; }
.render-auto { image-rendering: pixelated; }
@media screen and (min-width: 48em) {
 .render-auto-ns { image-rendering: auto; }
 .render-auto-ns { image-rendering: crisp-edges; }
 .render-auto-ns { image-rendering: pixelated; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .render-auto-m { image-rendering: auto; }
 .render-auto-m { image-rendering: crisp-edges; }
 .render-auto-m { image-rendering: pixelated; }
}
@media screen and (min-width: 64em) {
 .render-auto-l { image-rendering: auto; }
 .render-auto-l { image-rendering: crisp-edges; }
 .render-auto-l { image-rendering: pixelated; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT


# css-image-rendering 1.0.6

Css module of single purpose classes for image rendering

#### Stats

253 | 12 | 24
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-image-rendering
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-image-rendering
```

ssh:
```
git clone git@github.com:tachyons-css/css-image-rendering.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-image-rendering";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-image-rendering@1.0.6/css/css-image-rendering.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-image-rendering">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   IMAGE RENDERING
*/
.render-auto { image-rendering: auto; }
.render-auto { image-rendering: crisp-edges; }
.render-auto { -ms-interpolation-mode: nearest-neighbor; image-rendering: -webkit-optimize-contrast; image-rendering: -moz-crisp-edges; image-rendering: pixelated; }
@media screen and (min-width: 48em) {
 .render-auto-ns { image-rendering: auto; }
 .render-auto-ns { image-rendering: crisp-edges; }
 .render-auto-ns { -ms-interpolation-mode: nearest-neighbor; image-rendering: -webkit-optimize-contrast; image-rendering: -moz-crisp-edges; image-rendering: pixelated; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .render-auto-m { image-rendering: auto; }
 .render-auto-m { image-rendering: crisp-edges; }
 .render-auto-m { -ms-interpolation-mode: nearest-neighbor; image-rendering: -webkit-optimize-contrast; image-rendering: -moz-crisp-edges; image-rendering: pixelated; }
}
@media screen and (min-width: 64em) {
 .render-auto-l { image-rendering: auto; }
 .render-auto-l { image-rendering: crisp-edges; }
 .render-auto-l { -ms-interpolation-mode: nearest-neighbor; image-rendering: -webkit-optimize-contrast; image-rendering: -moz-crisp-edges; image-rendering: pixelated; }
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

ISC


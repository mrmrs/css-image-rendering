# css-image-rendering

Functional CSS for image-rendering

## Filesize

| File | Size |
|------|------|
| `dist/image-rendering.css` | 985 bytes |
| `dist/image-rendering.min.css` | 755 bytes (179 Gzipped) |

## Install

```sh
npm install css-image-rendering
```

## Usage

### Import

```css
@import "css-image-rendering";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-image-rendering/dist/image-rendering.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-image-rendering/dist/image-rendering.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.render-auto` | `image-rendering: auto;` |
| `.render-smooth` | `image-rendering: smooth;` |
| `.render-crisp` | `image-rendering: crisp-edges;` |
| `.render-pixelated` | `image-rendering: pixelated;` |
| `.render-auto-s` | `image-rendering: auto;` |
| `.render-smooth-s` | `image-rendering: smooth;` |
| `.render-crisp-s` | `image-rendering: crisp-edges;` |
| `.render-pixelated-s` | `image-rendering: pixelated;` |
| `.render-auto-m` | `image-rendering: auto;` |
| `.render-smooth-m` | `image-rendering: smooth;` |
| `.render-crisp-m` | `image-rendering: crisp-edges;` |
| `.render-pixelated-m` | `image-rendering: pixelated;` |
| `.render-auto-l` | `image-rendering: auto;` |
| `.render-smooth-l` | `image-rendering: smooth;` |
| `.render-crisp-l` | `image-rendering: crisp-edges;` |
| `.render-pixelated-l` | `image-rendering: pixelated;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.render-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/image-rendering.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/image-rendering.css` — formatted
- `dist/image-rendering.min.css` — minified

## License

MIT

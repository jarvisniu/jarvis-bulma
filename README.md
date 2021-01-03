# jarvis-bulma

Jarvis Niu's modified version of [Bulma](https://bulma.io/)

[
  [Docs / Demo](https://unpkg.com/jarvis-bulma/docs/index.html) -
  [GitHub](https://github.com/jarvisniu/jarvis-bulma) -
  [NPM](https://www.npmjs.com/package/jarvis-bulma) -
  [jsDelivr](https://www.jsdelivr.com/package/npm/jarvis-bulma)
]

## Differences

Differences from the original bulma:

- Not intrusive! Remove the `minireset.sass` and `generic.sass` to keep your styles. Instead, I recommend to use [tailwindcss/base.css](https://cdn.jsdelivr.net/npm/tailwindcss@2.0.2/dist/base.css) as a replacement.
- Remove the `helpers`. Leave it to [TailwindCSS](https://tailwindcss.com/).
- Replace colors `link`, `info`, `warning`, `danger` and `success` by `blue`, `cyan`, `yellow`, `red`, `green` and `orange`.
- Change primary color from `turquoise` to `blue`.

## Usage

### CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/jarvis-bulma" />

<!-- or minified -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/jarvis-bulma/css/bulma.min.css" />
```

### NPM

```
npm install jarvis-bulma
```

### Import CSS (with Source Maps)
```js
import 'jarvis-bulma'
// or
import 'jarvis-bulma/css/jarvis-bulma.css'
```

### Import SASS (Configuration)
```js
import 'jarvis-bulma/src/bulma.sass'
```

## Licence

MIT

# Fitter Happier Text

Performant, fully fluid headings

---

# Usage

Include `dist/fitter-happier-text.js` in your project or install from NPM:

```
npm install fitter-happier-text
```

Pass it a nodelist.

```js
var nodes = document.querySelectorAll('[data-fitter-happier-text]');
fitterHappierText(nodes);
```

Fitter Happier Text replaces each node with an SVG text node and sets the `viewBox` attribute based on its width and height.

To adjust for different fonts, use the `baseline` and `paddingY` options.

```js
fitterHappierText(nodes, { baseline: 14, paddingY: 2 });
```

## Usage with Gulpjs

To avoid client-side rendering, use a build tool like Gulpjs to replace HTML elements with SVG.

_Example TK_

---

MIT License


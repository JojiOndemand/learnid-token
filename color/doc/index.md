# Colors

```js script
import { html } from 'lit';
import '@divriots/dockit-core/css-showcases/dockit-css-showcases.define.js';
import './styles.css';
import '~/tokens/variables.css';
```

## Global

### blue colors

Primary colors of our brand.

```js story
export const primary = () => html`
  <dockit-css-showcases
    css-props-prefix="--figma-colors-blue"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

### Black colors

Black colors of our brand.

```js story
export const black = () => html`
  <dockit-css-showcases
    css-props-prefix="--figma-colors-black"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

### Red colors

Red colors of out brand.
```js story
export const red = () => html`
  <dockit-css-showcases
    css-props-prefix="--figma-colors-red"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

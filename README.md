# stitches-reset

![GitHub release](https://img.shields.io/github/release/hauptrolle/stitches-reset.svg) ![issues](https://img.shields.io/github/issues/hauptrolle/stitches-reset)

Eric Meyer's [Reset CSS](https://meyerweb.com/eric/tools/css/reset/) for [stitches](https://github.com/modulz/stitches).

Check out the demo on [codesandbox](https://codesandbox.io/s/zealous-hopper-5npr0?file=/src/App.tsx).

---

## Installation:

`yarn add stitches-reset`

or

`nom install stitches-reset`

## Usage:

```jsx
import * as React from "react";
import { reset } from "stitches-reset";
import { css } from "path-to/stitches.config.js";

css.global(reset);

const App = () => (
  <React.Fragment>
    <h1>Hi, I'm an app!</h1>
  </React.Fragment>
);
```

## Credits

All credit goes to Eric Meyer for reset.css and zacanger for the [styled-reset](https://github.com/zacanger/styled-reset/) example.

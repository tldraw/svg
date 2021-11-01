<div style="text-align: center; transform: scale(.5);">
  <img src="card-repo.png"/>
</div>

# @tldraw/svg

This package contains SVG utility functions used by [tldraw](https://tldraw.com).

💕 Love this library? Consider [becoming a sponsor](https://github.com/sponsors/steveruizok?frequency=recurring&sponsor=steveruizok).

## Installation

Use your package manager of choice to install `@tldraw/svg` and its peer dependencies.

```bash
yarn add @tldraw/svg
# or
npm i @tldraw/svg
```

## Usage

This library exports several functions that can be used to create SVG path data.

```tsx
import { moveTo, lineTo, bezierTo } from "@tldraw/vec"

const pathData = [
  moveTo([5, 5]),
  lineTo([10, 20]),
  bezierTo([12, 22], [16, 32], [16, 30]),
].join()
```

## Community

### Support

Need help? Please [open an issue](https://github.com/tldraw/svg/issues/new) for support.

### Discussion

Want to connect with other devs? Visit the [Discord channel](https://discord.gg/s4FXZ6fppJ).

### License

This project is licensed under MIT. If you're using the library in a commercial product, please consider [becoming a sponsor](https://github.com/sponsors/steveruizok?frequency=recurring&sponsor=steveruizok).

## Author

- [@steveruizok](https://twitter.com/steveruizok)

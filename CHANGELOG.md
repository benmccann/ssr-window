# Change Log

# [4.0.1](https://github.com/nolimits4web/ssr-window/compare/v4.0.0...v4.0.1) (2021-10-27)

### Features

- add "main" and "module" package.json fields ([bc2984a](https://github.com/nolimits4web/ssr-window/commit/bc2984aa787c6b2dc9f15d47805b36f7b26e23a2))

## [4.0.0](https://github.com/nolimits4web/ssr-window/compare/v3.0.0...v4.0.0) - Released on August 25, 2021

- Increase build target to `es6`
- Now package uses only `exports` field which exports ES module

## [4.0.0-beta.3](https://github.com/nolimits4web/ssr-window/compare/v4.0.0-beta.1...v4.0.0-beta.3) - Released on August 4, 2021

- Increase build target to `es6`

## [4.0.0-beta.1](https://github.com/nolimits4web/ssr-window/compare/v3.0.0...v4.0.0-beta.1) - Released on July 22, 2021

- Now package uses only `exports` field which exports ES module

## [3.0.0](https://github.com/nolimits4web/ssr-window/compare/v1.0.1...v2.0.0) - Released on November 9, 2020

- Now it uses getter functions for window and document to not to polute existing scope:

  ```js
  import { getWindow, getDocument } from 'ssr-window';

  const window = getWindow();
  const document = getDocument();
  ```

## [2.0.0](https://github.com/nolimits4web/ssr-window/compare/v1.0.1...v2.0.0) - Released on May 12, 2020

- Now it uses patching instead of creating window and document if they are already available
- Added `extend` method

## [1.0.1](https://github.com/nolimits4web/ssr-window/compare/v1.0.0...v1.0.1) - Released on July 18, 2018

- Simplified code structure to bypass rollup bugs

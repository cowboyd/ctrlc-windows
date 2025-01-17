# ctrlc-windows

## 2.2.0

### Minor Changes

- 06dabc0: Added support for arm64.

## 2.1.0

### Minor Changes

- fa3cfb4: Converted to `napi-rs`, and copy the built files directly into the dist folder. Also switched to `windows-rs` which is being supported by Microsoft directly. This shouldn't cause any breaking changes, but has much of the internals updated to a new setup.

## 2.0.0

### Major Changes

- 29e0b68: Switch to using the [n-api](https://nodejs.org/api/n-api.html) through the neon bindings. This provides more wholesale support for current and future versions of node, currently v10, v12, v14, and v16. (Previously ctrlc-windows@v1 only provided support for v10, v12 and v14.)

## 1.0.6

### Patch Changes

- 3298730: migrate to @mapbox/node-pre-gyp

## 1.0.5

### Patch Changes

- 696112a: Remove node 15 and 16 in release to undo broken 1.0.4

## 1.0.3

### Patch Changes

- 21ce6a2: Include the `not-windows.js` file to short circuit the build on
  non-windows platforms.
- 3add0af: Add node 15 and 16 for the binary release workflow

## 1.0.2

### Patch Changes

- e67ba75: do not even invoke `node-pre-gyp` on non-windows platforms as part of
  the install script. This silences warnings that are printed to the
  console for npm

## 1.0.1

### Patch Changes

- 21ae36b: improved error messages when things go wrong

## 0.2.0

### Minor Changes

- 254b553:

## 0.1.3

### Patch Changes

- d6af1a8: Fix release workflow v2

## 0.1.2

### Patch Changes

- 0b0d6cc: Fix release workflow

## 0.1.1

### Patch Changes

- f66aae5: Release workflow

# @use-gesture/core

## 10.2.4

### Patch Changes

- ae631004a: fix: change isNaN to Number.isNaN in dev mode

## 10.2.3

### Patch Changes

- 8302c5bfd: fix: prevent deprecated resolvers from applying in dev mode

## 10.2.2

### Patch Changes

- cffaba5ae: fix: logic error in intent detection

## 10.2.1

### Patch Changes

- 2f0cd466b: fix: release pointerId when PointerEvent is canceled. Should fix [#376](https://github.com/pmndrs/use-gesture/issues/376).

## 10.2.0

### Minor Changes

- b4e6181e7: Fix: should fix `transform` function doesn't have [0,0] origin. This required some pretty drastic internal changes hence the minor version bump.

## 10.1.6

### Patch Changes

- 9883b1c78: types: fix ReactDOMAttributes type

## 10.1.5

### Patch Changes

- 55505c071: fix: `event.buttons` condition was preventing `pointer.touch` from behaving properly.

## 10.1.4

### Patch Changes

- 090ba6b62: feat: allow pointer.buttons to accept an array or -1

## 10.1.3

### Patch Changes

- a9f99ce3c: feat: warn in dev mode if transform function return invalid values

## 10.1.2

### Patch Changes

- ed0073543: fix: add threshold to config resolver

## 10.1.1

### Patch Changes

- 8a0bfacb0: fix: Remove the console output statement.
- 8a0bfacb0: fix: Remove the console output statement.

## 10.1.0

### Minor Changes

- b67543ff7: Feat (drag): add the `pointer.buttons` in order to customize which [buttons combination](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent/buttons) will trigger the drag gesture.

## 10.0.3

### Patch Changes

- de01d7dbb: Sets state `canceled` / `_active` attributes synchronously with `cancel()`.

## 10.0.2

### Patch Changes

- a219d3f69: fix: make sure delay still set first to true when moving so that onDragStart can fire.

## 10.0.1

### Patch Changes

- c00c7b1: fix: add movement to offset when using wheel-based browsers on pinch

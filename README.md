# push-if

Push a element to the array if true.

## Installation

```
npm i push-if
```

## Usage

```js
import 'push-if'

const arr = ['a', 'b', 'c']

arr
  .pushIf(true, 'd') // => arr becomes ['a', 'b', 'c', 'd']
  .pushIf(false, 'f') // => arr will not change
```

> `pushIf()` will return the current array

# License

MIT License
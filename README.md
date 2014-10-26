all-stream
==========

**DEPRECATED: Use [concat-stream].**

Consume entire stream via buffer.

## Install

```sh
npm i --save all-stream
```

## Use

```js
var allStream = require('all-stream');

allStream(stream, function (err, data) {
  if (err) throw err;
  console.log(data);
});
```

[concat-stream]: https://www.npmjs.org/package/concat-stream

# erred

`erred` is a JS-less NPM Package for `HTTPErrors` that builds on publish

## Usage

Import or require the errors and use them in place of your normal errors

```javascript
const { NotFound, BadRequest } = require('@hndlr/errors')

let error = new NotFound('...')
error.status // 404

error = new BadRequest('...')
error.status // 400
```

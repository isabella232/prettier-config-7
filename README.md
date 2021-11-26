# `@mirohq/prettier-config`

![](https://img.shields.io/npm/v/@mirohq/prettier-config.svg?style=flat-square)

## Usage

**Install**:

> Requires `prettier >= 2.4`

```bash
npm install --dev @mirohq/prettier-config
```

**Edit `package.json`**:

```json
{
  "prettier": "@mirohq/prettier-config"
}
```

**or `prettier.config.js`**:

```js
module.exports = require('@mirohq/prettier-config')
```

You can also override [configuration](https://prettier.io/docs/en/options.html)
like this

```js
module.exports = {
  ...require("@mirohq/prettier-config")
  semi: true,
}
```

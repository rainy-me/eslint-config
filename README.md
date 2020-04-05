# @kalafina/eslint-config

forked from [kalafina's awesome eslint-config 🚀](https://github.com/kalafina/eslint-config)

## Install package

```sh
npm i -D @kalafina/eslint-config
```

## Install peer dependencies

```sh
# required
npm i -D typescript
# optional
npm i react
```

## Usage

.eslintrc.js

```js
module.exports = {
  extends: ['@kalafina'],
  parserOptions: {
    project: './tsconfig.json',
    tsconfigRootDir: '.'
  }
};
```

# eslint-config-unicorn-camelcase

[![Build Status](https://travis-ci.com/timche/eslint-config-unicorn-camelcase.svg?branch=master)](https://travis-ci.com/timche/eslint-config-unicorn-camelcase)
[![npm](https://img.shields.io/npm/v/eslint-config-unicorn-camelcase.svg)](https://www.npmjs.com/package/eslint-config-unicorn-camelcase)
[![npm](https://img.shields.io/npm/dm/eslint-config-unicorn-camelcase.svg)](https://www.npmjs.com/package/eslint-config-unicorn-camelcase)

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) for [unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn) with [camelCase filename](https://github.com/sindresorhus/eslint-plugin-unicorn/blob/master/docs/rules/filename-case.md#camelcase)

## Install

```
npm install --save-dev eslint-config-unicorn-camelcase
```

## Usage

`.eslintrc`

```json
{
  "extends": "unicorn-camelcase"
}
```

`package.json`

```json
{
  "eslintConfig": {
    "extends": "unicorn-camelcase"
  }
}
```

# @naturalclar/eslint-config

Custom eslint config for my personal projects

Includes prettier and eslint-config for typescript project

The config is based of off `@react-native-community/eslint-config` with some modification for my needs.

## Installation

```
yarn add -D eslint @naturalclar/eslint-config
```

## Setup

Create an `.eslintrc.js` in your root directory of the project with the following settings

```js
module.exports = {
  extends: "@naturalclar"
}
```
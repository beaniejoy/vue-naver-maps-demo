# vue-naver-maps-demo

Naver Maps API를 Vue Framework 환경 내에 적용해보는 Demo Project입니다.

## Setup

### Vue Cli Installation
```
npm i -g @vue/cli
```
### Create Vue Project
```
vue create <project_name>
```
여기서는 Vue2 버전을 사용했습니다. Vue3 버전은 몇몇 브라우저에 아직 호환이 안되는 것이 있는듯 합니다.

## Plugins

- vuex
- vue-router
- vuetify

## ESLint

VSCode 환경에서 `prettier`, `ESLint`를 사용해 코드 포맷을 적용했습니다.
```
npm i -D --save-exact prettier
npm i -D eslint-config-prettier eslint-plugin-prettier
```
`ESLint`와 `Prettier`간 Conflict를 방지해줍니다.

```json
// .eslintrc
{
  "extends": [
    "plugin:vue/essential",
    "eslint:recommended",
    "plugin:prettier/recommended"
  ],
  "parserOptions": {
    "parser": "babel-eslint",
    "ecmaVersion": 7,
    "sourceType": "module",
  },
}
``` 

## Naver Maps API

[NAVER Maps API Document](https://navermaps.github.io/maps.js.ncp/)

```html
<!-- index.html -->
<script type="text/javascript" src="https://openapi.map.naver.com/openapi/v3/maps.js?ncpClientId=[ClientID]"></script>
```

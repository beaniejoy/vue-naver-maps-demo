# vue-naver-maps-demo

Naver Maps API를 Vue Framework 환경 내에 적용해보는 Demo Project

## Setup

### Vue Cli Installation
```
npm i -g @vue/cli
```
### Create Vue Project
```
vue create <project_name>
```

## Plugins

- vuex
- vue-router
- vuetify

## ESLint Settings

```
npm i -D --save-exact prettier
npm i -D eslint-config-prettier eslint-plugin-prettier
```
`ESLint`와 `Prettier`간 Conflict를 방지해준다.

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
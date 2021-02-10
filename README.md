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
  ...
  // eslint의 룰을 기본 권장설정으로 설정
  "extends": [
    "plugin:vue/essential",
    "eslint:recommended",
    "plugin:prettier/recommended"
  ],
  // 코드를 해석하는 parser에 대한 설정
  "parserOptions": {
    "parser": "babel-eslint",
    // 자바스크립트 버전, 7은 ECMA2016
    "ecmaVersion": 7,
    // 모듈 export를 위해 import, export를 사용 가능여부를 설정, script는 사용불가
    "sourceType": "module",
    ...
  },
  ...
}
``` 
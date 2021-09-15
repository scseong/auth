# Project Settings

## Prettier, Eslint

`npm i -D eslint`
`npm i -D prettier eslint-plugin-prettier eslint-config-prettier`

## 리액트 절대경로 설정

`npm i @craco/craco craco-alias`

**파일생성**

- 📄 jsconfig.json

- 📄 craco.config.js

```
📄 package.json // react-scripts를 craco로 변경

"scripts": {
  "start": "craco start",
  "build": "craco build",
  "test": "craco test",
  "eject": "react-scripts eject"
},
```

**🚨 Error: Delete `␍`eslint prettier/prettier**

```json
📄 .eslintrc
// 추가
"rules": {
  "prettier/prettier": ["error", {
    "endOfLine":"auto"
   }]
}
```

## 라우터 설정

`npm react-router react-router-dom`

## 코드 스플리팅

`npm i @loadable/component`


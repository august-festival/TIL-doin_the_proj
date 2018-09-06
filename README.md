# TIL-doin_the_proj

프로젝트를 하면서 알게된 것들

# VSCode

## plugin

1. Beautify
1. jshint
1. prettier
   ```
   "editor.formatOnSave": true,
   "javascript.format.enable": false,
   "prettier.eslintIntegration": true
   ```
1. vetur
1. GitLens



# Mocha

- window에서 테스트코드 실행(npm test 실행) 할 경우 package.json 환경 설정
  ```
  "scripts": {
    "test": "node_modules/.bin/mocha find ./test/ -name '*.spec.js' --recursive",
    "start": "node ./bin/www"
  },
  ```

   

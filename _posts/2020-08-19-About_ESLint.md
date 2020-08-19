---
title: "About ESLint"
date: 2020-08-19 23:09:00 -0400
categories: jekyll update
---
# ESLint란 무엇인가?

ESLint는 JavaScript 코드에서 발견 된 문제 패턴을 식별하기위한 정적 코드 분석 도구입니다. ESLint의 규칙은 구성 가능하며 사용자 정의 된 규칙을 정의하고로드 할 수 있습니다. ESLint는 코드 품질과 코딩 스타일 문제를 모두 다룹니다. [위키백과(영어)](https://en.wikipedia.org/wiki/ESLint)

# 어떻게 사용하는가?

## npm 모듈 설치

```bash
npm install --save-dev babel-eslint
npm install --save-dev eslint-config-airbnb
npm install --save-dev eslint-plugin-import
npm install --save-dev eslint-plugin-jsx-a11y
npm install --save-dev eslint-plugin-react
npm install --save-dev eslint-plugin-react-hooks
```

save-dev 옵션: 개발용으로만 사용하고 싶은 경우 추가.
설치가 완료되면 package.json 내의 devDependencies에 모듈 네임이 추가된다.

## atom 패키지 설치

https://atom.io/packages/linter-eslint
위 url에서 linter-eslint 패키지를 atom에 install한다.

# 참고자료

* [Eslintで構文チェック](https://www.udemy.com/course/react-native-ios-android/learn/lecture/8436162#overview)
* [Eslintの設定を変更する](https://www.udemy.com/course/react-native-ios-android/learn/lecture/8436168#overview)

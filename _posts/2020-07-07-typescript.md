---
published: true
layout: post
date: '2020-07-07 13:57 +0900'
---
## TypeScript Overview
TypeScript의 정의
- 프로그래밍 언어
- Compiled Language이다. JS 문법에 그대로 추가해서 사용가능하다.
- Js는 Interpreted Language이다. JS는 타입에서 비교적 자유롭다.
TypeScript의 특징
- 정적타입언어이다.
- TypeScript는 Compiler를 통해, JS라는 결과물이 나온다.
정적타입언어(string,int) vs 동적타입언어(var, let)
- 정적타입언어는 테스트를 많이 안해도, 초기에 타입으로 인한 문제를 빠르게 잡아준다.

## 개발 환경 구축
Runtime 환경, Editor, Complier
- node.js : Chrome의 V8 Javascript Engine을 사용하여, JS를 해석하고, OS 레벨에서의 API를 제공하는 서버사이드용 JS 런타임 환경
- complier 모듈을 npm에서 제공
- browser : JS를 해석하고, DOM을 제어할 수 있도록 하는 JS 런타임 환경
개발 환경 구축
- node.js 설치 : https://nodejs.org 6.10.3
- nvm (node.js version manager : node.js의 버전을 자유롭게 변경)
- nvm install 6.10.2
- nvm use 6.10.3
- node -v
- npm init -y			  //npm 기본 설정
- npm i typescript -g	  //typescript complier 모듈 Global Install

- tsc (xxx.ts 파일 경로)
- tsc (ts.config 파일이 있을 경우, tsc만 쳐도, ts파일들을 컴파일 해준다.)
- tsc -w (Watch mode 자동으로 변화를 Compile해주는 것, Gulp 모듈과 비슷하다)

- ./node_modules/.bin/tsc
- package.json 폴더 내, compile option에 tsc 추가
- 타입스크립트 형식 확장자의 경우 .ts 
- ts.config 파일 내부에, 어떻게 js파일을 생성시킬 것인지 정의





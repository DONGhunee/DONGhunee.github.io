---
layout: post
title: "[React] 프론트엔드의 빌드 시스템"
subtitle: "프론트엔드의 빌드 시스템"
categories: "study"
tags: "react"
---

# 1. Babel

바벨은 코드를 추상화 시켜 다운그레이드 하는 트랜스 파일러입니다.

대부분 코드를 작성할 때 ES6 이후 문법을 사용할 것 입니다.
그런데 아직 구형 브라우저의 경우 ES6이후에 추가된 문법을 지원하지 않기 때문에 바벨을 통해 다운그레이드 된 문법을 사용한다.

<br>

# Polyfill

충천솜이라는 의미를 가지고 있습니다.
브라우저에서 지원하지 않는 코드를 사용 가능한 코드나 플러그인으로 만들어 줍니다.

> 바벨만 사용한다고 해서 ES6 이후의 최신 문법이 모두 적용되는 것이 아닙니다. 즉 바벨을 서포트 해주는 역할

<br>

# Node.js

최신 문법으로 개발할 때 사용하는 문법을 웹팩이나 바벨 같은 것들을 활용해서 개발하려면 이 모든 것들이 node.js 위에서 구동되기 때문에 가히 필수적입니다. 또한 빌드 자동화를 지원한다.

<br>

# ESLint & Prettier

## ESLint

코드 퀄리티와 포멧팅을 함께 지원해줍니다.

> 포멧팅 : 일관된 코드 스타일을 유지하도록 하고 개발자들이 쉽게 읽히는 코드를 만들어 줍니다.

## Prettier

Prettier는 ESLint에 더하여 코드를 더 이쁘게 만들어 줍니다.

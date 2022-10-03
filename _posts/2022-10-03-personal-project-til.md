---
layout: post
title: 10.03 공부 TIL
date: 2022-10-03 20:15:00 +0900
description: 22.10.03 공부 TIL
img: post/2022-09-15/starting-1.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: []
---

10월 3일에 진행한 개인 프로젝트 TIL

# Facts

- 노드-리액트 기본 강의 수강
  - 강의: 인프런 - 따라하며 배우는 노드-리액트 기본 (John Ahn)
- NestJS(Backend), React(Frontend) 조합의 One Repo로 구성

# Feelings

- 공부의 사고가 확장되는건 좋은데, 가끔 내 스스로 너무 방대해져서 걱정이다.. 한 번에 하나씩 하자.
- 너무 한 번에 잘하려고 하지 말자.. 빨리빨리 완벽하게 하려고 하니 오지게 스트레스 받는다. ㅜ 숨 못 쉬겠슈

# Findings

- npx
  - npm 5.2 버전 이후부터 제공하는 모듈인데, 보통 보일러플레이트 프로젝트를 다운받을 때 사용한다고 한다. 1회성으로 실행만 하고 지울 때 사용한다.
  - 모듈을 로컬에 설치하지 않고 매번 최신 버전의 파일만 임시로 다운받고 실행시킨 뒤, 실행되고 나면 원래 파일이 없어짐.
  - 공부 소스[npx공부소스](https://ljh86029926.gitbook.io/coding-apple-react/undefined/npm-npx)
- 쿠키, 세션, 웹스토리지(세션/로컬스토리지) 차이점
  - 보통 쿠키를 많이 썼었어서, 세션과 웹스토리지는 감이 좀 안 온다. 자바 사이드 프로젝트로 한번 만들어봐도 좋겠다.
  - 공부 소스1[쿠키세션스토리지공부소스](https://doqtqu.tistory.com/306)
  - 공부 소스2[쿠키공부소스](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
- CSRF
  - 위의 "쿠키, 세션, 웹스토리지"를 공부하다가 발견한 것
  - 공부 소스[CSRF공부소스](https://itstory.tk/entry/CSRF-%EA%B3%B5%EA%B2%A9%EC%9D%B4%EB%9E%80-%EA%B7%B8%EB%A6%AC%EA%B3%A0-CSRF-%EB%B0%A9%EC%96%B4-%EB%B0%A9%EB%B2%95)
- react
  - 프론트엔드 라이브러리
  - 모듈과 비슷한 "컴포넌트"로 이루어져 있어 재사용성 뛰어남
  - Virtual DOM을 활용하여 빠른 렌더링 속도
    - Real DOM vs Virtual DOM
      - Real DOM : 10 개의 리스트가 있고, 이 중 하나가 변경되면 전부 다 재조회 해야 함. 헤비한 작업
      - Virtual DOM: 10개의 리스트가 있고, 이 중 하나가 변경되었을 때 실제 변경된 리스트 항목만 찾아내서 (Diffing) 얘만 변경함
    - Virtual DOM은 Real DOM과 같은 프로퍼티를 갖고 있지만 가볍게 복사한 버전
    - Virtual DOM이 변경된 요소만 빨리 찾아내는 원리
      - (1) JSX를 렌더링한다. 이렇게 하면 Virtual DOM이 업데이트 됨
      - (2) Virtual DOM은 이전 버전의 Virtual DOM 의 스냅샷을 가지고 있다. 이것과 비교대조한다. (Diffing)
      - (3) 바뀐 부분만 RealDOM을 변경한다.
- babel, webpack
  - babel : 최신 자바스크립트 문법을 지원하지 않는 옛날 브라우저들에 최신 자바스크립트 코드가 돌아갈 수 있도록 변환시켜주는 라이브러리
  - webpack: 예전에는 html-js-css 만으로 간단하게 이루어져 있었던 프론트 구조가 많이 복잡해짐에 따라, 다양한 프론트엔드 구성 파일들을 bundle 시켜주는 라이브러리.
  - react 앱을 구성할 때 babel & webpack 설정하는게 한참 걸렸는데, creat-react-app boilerplate를 통해 간단하게 설정 가능하다.

# Bad

- 공부하면서 자꾸 확장되는 느낌이다.. 스스로의 욕심에 지친다. ㅜ
- 빨리 해야되는데, 싶어서 마음이 자꾸 급해진다.

# Affirmation

- 즐기면서 하자.
- 직접 부딪혀서 내 것으로 만들자.
- 공부의 최종 목적을 잊어버리지 말자.
- 기간 설정을 하자.

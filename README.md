# **PortFolio Web Project**

첫 웹사이트를 구현한 포트폴리오 프로젝트

21.11.18 - 21.11.26

[Github](https://github.com/Seokho0120/Portfolio.git) | [회고](https://velog.io/@leesegho/%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8) | [구현영상](https://seokho0120.github.io/Portfolio/)

## Tech Stack

HTML | CSS | Java Script

## Overview

기획과 디자인, 개발까지 전체적인 사이클을 심플하게 구성한 반응형 웹 포트폴리오 프로젝트 입니다.

## What did I do

### 웹 포트폴리오 구현

- 순수 HTML, CSS를 활용했으며 Vanilla JS로 동적인 요소를 추가했습니다.
- 기초적인 기획 (레이아웃, 디자인)과 스타일링으로 반응형 사이트를 구현했습니다.

### HTML, CSS 기초 심화 학습

- Flex, Position, Transform 등 속성을 이용해 요소를 원하는 위치에 배치하며 레이아웃을 구성했습니다.
- BEM(Block Element Modifier)을 활용한 클래스명 작성 및 CSS 스타일링 했습니다.
- media queries를 이용해 반응형 웹 사이트로 구현 했습니다.

### Javascript 를 학습하며 동적 요소 구현

- Navbar의 높이 이상으로 Scrolling이 발생하면 Navbar의 투명도가 조정됩니다.
- 섹션의 id를 받아 scrollInToView함수를 이용해 원하는 위치로 스크롤링 및 이동이 가능한 Button을 구현했습니다.
- 각각의 프로젝트에 data-type을 설정해 필터 버튼을 클릭 시 해당하는 프로젝트만 렌더링 됩니다.
- 필터 버튼에 프로젝트 개수를 나타내는 숫자를 클릭 시 undefined가 나오는 블로커를 만났습니다. 버튼안의 span에 data-type이
  설정되어 있지 않은것으로 판단되어, Source 탭에서 브레이크 포인트를 설정 후 디버깅을 통해 해결했습니다.

## 구현영상

스크롤 시 Navbar & Home 화면의 투명도 변화를 구현했습니다.

![navbar home trasparent 변화](https://user-images.githubusercontent.com/93597794/160514122-82713ebf-1aca-466e-a146-09c5ba567a45.gif)

클릭 시 원하는 Section으로 이동하는 버튼을 구현했습니다.

![Click to Section 버튼](https://user-images.githubusercontent.com/93597794/160514391-c2c56288-21ed-4c59-a166-2999486f8107.gif)

카테고리 버튼을 클릭 시 전체적인 animation이 일어나면서 원하는 내용을 filtering 합니다.

![filtering animation 구현](https://user-images.githubusercontent.com/93597794/160514395-8c392548-b8e6-450e-a81c-c7dc72d5d8f7.gif)

미디어 쿼리를 이용해 반응형 웹사이트를 디자인했습니다.

![반응형 구현-min](https://user-images.githubusercontent.com/93597794/160514376-50eecf22-84c4-4b4c-89ac-5598d4b71694.gif)

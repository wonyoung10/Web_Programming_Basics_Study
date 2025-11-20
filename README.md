# 웹 프로그래밍 기초 학습 (Web Programming Basics Study)

## 목차
- [0828 (1주차 학습)](#0828-1주차-학습)  
- [0904 (2주차 학습)](#0904-2주차-학습)  
- [0911 (3주차 학습)](#0911-3주차-학습)  
- [0918 (4주차 학습)](#0918-4주차-학습)  
- [0925 (5주차 학습)](#0925-5주차-학습)
---
j.s 는 시험 범위 x
반응형은 수행 평가

---

## 0828 (1주차 학습)  
**주제: HTML 역사, 기초 문법**

### 학습 내용
- HTML 기본 구조 (`<html>, <head>, <body>`)  
- 텍스트 태그 (`<b>, <font>`)  
- 링크 & 이미지 (`<a>, <img>`)  

---

## 0904 (2주차 학습)  
**주제: 제목 태그, 주석, 단락, 목록, 표**

### 학습 내용
- 제목 태그 (`<h1> ~ <h6>`)  
- 주석 (`<!-- -->`)  
- 단락 및 구분선 (`<p>, <hr>, <del>`)  
- 목록 (`<ol>, <ul>, <li>`)  
- 표 (`<table>, <tr>, <td>, <th>, colspan, rowspan`)  

---

## 0911 (3주차 학습)  
**주제: 문제 풀이 및 미디어, 오디오, 비디오, 입력양식 태그**

### 학습 내용
- **문제 풀이**: p.92 연습 문제  
- **미디어 태그**
  - 이미지 (`<img>`)
  - 오디오 (`<audio> <source>`)
  - 비디오 (`<video>`)
- **입력 양식 태그**
  - `<input>` (다양한 타입)  
  - `<textarea>`, `<select> <option>`  
  - `<form>` + `action`, `method`  
  - `<fieldset>, <legend>`  
- **공간 분할 태그**
  - 블록: `<div>`  
  - 인라인: `<span>`  
  - 시멘틱 태그: `<header>, <nav>, <aside>, <section>, <article>, <footer>`  

---

## 0918 (4주차 학습)  
**주제: CSS 기초 스타일링, 색상과 선택자 연습**

### 학습 내용
- **CSS 선택자**
  - 전체 선택자 (`*`)  
  - 아이디 선택자 (`#id`)  
  - 클래스 선택자 (`.class`)  
  - 태그 선택자 (`div, p, li 등`)  
  - 속성 선택자 (`input[type="text"], input[type="password"]`)  
  - 후손 선택자 (`div ul li`)  
  - 자식 선택자 (`div > ul > li`)  
  - 구조 선택자 (`:first-child, :last-child, :nth-child(n)`)  

- **텍스트 및 색상 스타일**
  - `color` 속성으로 텍스트 색상 지정  
  - 기본 색상(red, orange, yellow, green, blue 등) 활용  

- **예시 코드**
  ```css
  #a1 { color: red; }
  #a2 { color: orange; }
  .a3 { color: yellow; }
  .a4 { color: green; }
  .a5 { color: blue; }
  input[type="text"] { background-color: greenyellow; }
  input[type="password"] { background-color: yellow; }
  a,b


## 0925 (5주차 학습)  
**주제: CSS 속성 기초, 반응/상태 선택자, 배경 속성**  

### 학습 내용
- **id / class 차이**
  - `id`: 한 문서에서 **한 번만 사용 가능**
  - `class`: 여러 요소에서 **여러 번 사용 가능**

- **반응 선택자 (User Action Pseudo-classes)**
  - `h1:active { color: aqua; }` → 클릭 시 색상 변경  
  - `h1:hover { color: rgb(244,123,242); }` → 마우스 올렸을 때 색상 변경  

- **상태 선택자 (Form State Pseudo-classes)**
  - `:checked` → 체크박스/라디오 선택 상태  
  - `:focus` → 입력 요소 활성화 상태  
  - `:enabled`, `:disabled` → 사용 가능/불가능한 입력 요소  

- **인라인 / 블록 요소 구별**
  - `block`: `div`, `p`, `h1` 등 → 한 줄 전체 차지  
  - `inline`: `span`, `a`, `img` 등 → 내용 크기만큼 차지  
  - `inline-block`: inline처럼 흐르되 block 속성 적용 가능  

- **배경 속성 (Background Property)**
  - `background-image`: 배경 이미지 삽입  
  - `background-size`: 배경 이미지 크기 조정  
  - `background-repeat`: 반복 여부 (`no-repeat`)  
  - `background-attachment`: 고정/스크롤 (`fixed`)  
  - `background-position`: 위치 조정 (예: `0px 50%`)  

- **CSS 박스 속성 (Box Model 기초)**  
  - `border`: 테두리 (solid, dotted, dashed 등)  
  - `margin`: 요소 바깥 여백 (상하좌우 지정 가능)  
  - `padding`: 요소 안쪽 여백  
  - `border-radius`: 둥근 모서리 (원형 버튼 등 가능)  

- **버튼 스타일링 예시**  
  - `box-shadow`: 그림자 효과  
  - `linear-gradient`: 배경 색상 그라데이션  
  - `:hover`, `:active`를 이용한 버튼 인터랙션  

## 1002 (6주차 학습)  
**주제: 글자 속성, 버튼 스타일링, 위치 속성**

### 학습 내용
- **글꼴 관련**
  - `sans-serif` → 고딕체  
  - `serif` → 명조체  
  - `font-size` 단위  
    - `px` (고정 크기), `rem` (루트 기준), `large`, `small` 등  
  - `font-style`: `italic`, `oblique`  
  - `font-weight`: `bold`  

- **HTML vs CSS 글자 기울기**
  - `<i>, <em>` 같은 **HTML 태그**가 CSS `font-style` 속성보다 **우선 적용됨**

- **정렬 속성**
  - `text-align: center;` → 텍스트 중앙 정렬  

- **버튼 스타일링**
  - `border`, `border-radius`: 테두리 & 둥근 모서리  
  - `box-shadow`: 그림자 효과  
  - `text-decoration: none;` → 링크 밑줄 제거  
  - `line-height`로 버튼 내 텍스트 수직 정렬  

- **위치 속성 (Position & Z-index)**
  - `position: relative / absolute` → 요소 배치 기준 다름  
  - `z-index` → 요소 쌓이는 순서 지정  
  - `overflow` → 영역 넘침 처리 (`hidden`, `scroll`, `auto`)  

- **시험 범위**
  - 교재 p.202까지  


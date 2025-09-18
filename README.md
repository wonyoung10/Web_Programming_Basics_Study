# 웹 프로그래밍 기초 학습 (Web Programming Basics Study)

## 목차
- [0828 (1주차 학습)](#0828-1주차-학습)  
- [0904 (2주차 학습)](#0904-2주차-학습)  
- [0911 (3주차 학습)](#0911-3주차-학습)  
- [0918 (4주차 학습)](#0918-4주차-학습)  
- [추가 주차 템플릿](#추가-주차-템플릿)  
- [정리](#정리)  

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

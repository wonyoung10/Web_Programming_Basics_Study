# 웹 프로그래밍 기초 학습 (Web Programming Basics Study)

## 목차
- [0828 (1주차 학습)](#0828-1주차-학습)  
- [0904 (2주차 학습)](#0904-2주차-학습)  
- [0911 (3주차 학습)](#0911-3주차-학습)  
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
    - `type="text|password|file|checkbox|radio|hidden|submit|reset|button|image"`
    - 주요 속성:
      - `name` : 입력값을 서버로 전송할 때 사용하는 이름  
      - `id` : 고유 식별자 (라벨 `<label for="id">`와 연결할 때 사용)  
      - `value` : 기본값 설정  
      - `placeholder` : 입력창에 힌트 텍스트 표시  
      - `required` : 필수 입력값 설정  
      - `readonly` : 읽기 전용 입력칸  
      - `disabled` : 비활성화 상태  
      - `maxlength` : 입력 가능한 최대 글자 수  
      - `size` : 입력창의 크기(가로 길이)  
      - `checked` : 체크박스/라디오 버튼 기본 선택 여부  
      - `multiple` : 파일 업로드/이메일 입력 시 여러 개 선택 가능  
      - `autocomplete` : 자동완성 여부 (on/off)  
    - 예시:
      ```html
      <input type="text" name="username" id="username" placeholder="아이디 입력" required>
      <input type="password" name="password" id="password" placeholder="비밀번호 입력" required>
      <input type="checkbox" name="agree" checked> 이용약관 동의
      <input type="file" name="upload" multiple>
      ```
  - `<textarea>` (여러 줄 입력 상자)  
  - `<select> <option>` (드롭다운 선택)  
  - `<form>` + `action`, `method` (get/post)  
  - `<fieldset>, <legend>` (입력 그룹 구분)
- **공간 분할 태그**
  - 블록: `<div>`  
  - 인라인: `<span>`  
  - 시멘틱 태그: `<header>, <nav>, <aside>, <section>, <article>, <footer>`  

---

## 추가 주차 템플릿
> 새로운 주차를 추가할 때 아래 형식을 복사해서 사용하세요.

## 0918 (4주차 학습)  
**주제: (여기에 학습 주제 작성)**

### 학습 내용
- 태그/속성 1  
- 태그/속성 2  
- 태그/속성 3  

---

## 정리  
- **0828 (1주차)** : HTML 기본 구조, 텍스트 태그, 링크 & 이미지  
- **0904 (2주차)** : 제목, 주석, 단락, 구분선, 목록, 표  
- **0911 (3주차)** : 문제 풀이, 미디어·오디오·비디오, 입력 양식, 공간 분할 태그  

# HTTP_The_Definitive_Guide

### ✔️ 목표

<img src = "https://contents.kyobobook.co.kr/sih/fit-in/458x0/pdt/9788966261208.jpg" width ="200px">

<a href = "https://product.kyobobook.co.kr/detail/S000001033001">HTTP 완벽 가이드</a> 책을 통해 HTTP를 깊게 학습합니다.

--- 
### [ 운영 방식 ]

1. 해당 주차의 글을 읽고 각자 `quesition`에 해당하는 부분을 글로 정리하여 해당 주차 파일 아래에 `정리_{이름}.md` 파일 형태로 커밋한다.
2. 추가로 궁금한 부분/공부했으면 하는 부분을 issue에 추가한다. **(필수)**
  1. 스터디 전 같이 학습해야 하는 issue가 있을 경우 question에 추가한다.
  2. 추가된 question은 1번에서 정리된 파일에 정리한다.
3. 담당자는 스터디 당일에 뽑기를 통해 결정하며 정리한 question을 발표한다.
5. 해당 주차에 추가된 issue 처리는 issue 별로 스터디 당일 발표자를 선정하여 답글을 달고 차주 스터디 때 발표한다.

#### ✔️ mark down 파일 template

```
---
data: 발표 날짜
---
# [chapter name]

## question
<details>
<summary>Q: 질문내용</summary>
<div markdown="1">       
답변
</div>
<details>
<summary>Q: 질문내용</summary>
<div markdown="1">       
답변
</div>

```

#### ✔️ 커밋 컨벤션

- 정리본 업로드 시
  ```
  Init[chapter02.md]: chater02 요약 정리 추가
  ```

- 정리본 수정 시
  ```
  Modify[chapter02.md]: 무슨 내용 추가

  - 무슨 부분을 추가 하였음.
  ```

#### ✔️ issue 추가 컨벤션

- 주차와 장에 해당하는 라벨을 추가한다. (없을 경우 라벨 생성)

```
---
name: Q&A 등록
about: 공부하다 공유하고싶은 지식을 질문 형태로 공유합니다.
title: "[챕터이름] 질문"
labels: Q&A
assignees: luminoustone

---

- keyword: [ ]
- page: [p.32]

## 설명
질문형식으로 적어주세요.

Assignee는 해당 주차 때 선정된 분으로 설정해 주세요.

```

---

### [ 스터디 기간 ]

| week | Topic                                  | Question                                                                                                            |
|:----:|----------------------------------------|---------------------------------------------------------------------------------------------------------------------|
|  1   | 1장. HTTP 개관 <br> 2장. URL과 리소스          | 01. 웹 브라우저가 HTML을 보여주기 까지의 과정 <br> 02. CORS 정책에서 왜 포트번호가 다르면 다른 Origin(출처)로 인식할까? <br> 03. URL을 쓰는 이유는 무엇일까?        |
|  2   | 3장. HTTP 메시지 <br> 4장 커넥션 관리            | 01. HTTP 지연은 왜 발생할까? <br> 02. HTTP 1.0과 1.1의 차이가 무엇일까? <br> 03. HTTP 메소드의 멱등성, 그리고 안전한 메서드 <br> 04. TCP와 UDP의 차이 |
|  3   | 5장. 웹 서버                               | 01. 요청 메시지를 파싱할 때, 웹 서버는 어떤 일을 할까?                                                                                  |
|  4   | 6장. 프락시 <br> 7장. 캐시                    | 01. 프록시 서버란 무엇이며, 프록시서버가 필요한 이유가 무엇일까? <br> 02. 리버스 프락시란 무엇이며 언제 사용될까? <br> 03. 웹 캐시를 다루는 방법                        |
|  5   | 8장. 통합점 : 게이트웨이, 터널, 릴레이 <br> 9장. 웹 로봇 | 01. 서치엔진은 어떻게 작동할까?                                                                                                 |
|  6   | 10장 HTTP/2.0 <br> 11장. 클라이언트 식별과 쿠키    | 01. HTTP의 진화 과정 <br> 02. 쿠키 SameSite 헤더 <br> 03. 쿠키와 세션의 차이                                                         |
|  7   | 12장. 기본 인증 <br> 13장. 다이제스트 인증          | 01. Base-64란 무엇일까? 02. Basic 인증과 Bearer 인증이란?                                                                       |
|  8   | 14장. 보안 HTTP <br> 15장. 엔터티와 인코딩        | 01. HTTPS와 SSL 인증서란 무엇일까? <br> 02. HTTP 3.0에서의 전송 인코딩                                                               |
|  9   | 16장. 국제화 <br> 17장. 내용 협상과 트랜스 코딩       |                                                                                                                     |
|  10  | 18장. 웹 호스팅 <br> 19장. 배포 시스템            |                                                                                                                     |
|  11  | 20장. 리다이렉션과 부하 균형 <br> 21장. 로깅과 사용 추적  |                                                                                                                     |

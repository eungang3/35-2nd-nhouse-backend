# 내일의 집 nhouse (위코드 35기 2차 프로젝트)
- 내일의 집은 오늘의 집 쇼핑몰을 클론코딩한 프로젝트입니다. 
- 개발에 집중하기 위해 기획, 디자인은 참고하고 기능은 직접 구현하였습니다.
- 링크 : http://13.127.1.227:8000/

<br>


## 1. 선정 이유
- 커뮤니티와 스토어가 밀접하게 연동되어 있는 구조
   + 복잡한 모델링 공부 가능
   + SNS(커뮤니티) 사이트와 커머스(스토어)사이트를 둘 다 구현해볼 수 있음

- 소셜 로그인 기능 
   + 외부 API를 이용하여 인증, 인가하는 법을 익힐 수 있음

- 포스트 작성 기능 
   + AWS S3를 사용해서 장고와 외부 애플리케이션을 연동하는 법을 익힐 수 있음

<br>


## 2. 개발 인원
- 백엔드 2명 : 김민지, 조예슬
- 프론트엔드 3명 : 오창훈(PM), 김광희, 정훈조

<br>

## 3. 기간
2022.8.1 ~ 8.12(2주)

<br>

## 4. 백엔드 역할
- 김민지
   - DB 모델링
   - 글쓰기 API(s3)
   - 카테고리 API
   - 상품상세/상품목록 API
   - AWS 배포 
   
- 조예슬
   - DB 모델링
   - SNS 로그인 API
   - 포스트상세/포스트 목록 API
   - 팔로우 API
   
<br>

## 5. 백엔드 기술 스택
- Back-end : Python, Django, JWT, Bcrypt, Miniconda
- Database : dbdiagram.io, MySQL
- HTTP : Postman
- Common : Trello, Slack, Git & Github

<br>

## 6. API 명세서
https://www.notion.so/API-aba14d6d95e04d9ca1723f5467d1df3b

<br>

## 7. 시연 영상
https://www.youtube.com/watch?v=xwOui_m09ZI&t=1s

<br>

![카카오-로그인](https://user-images.githubusercontent.com/47664802/184307548-414db957-5a57-493d-a0bb-fff7f12aa49e.gif)
<br>

![팔로잉-추천](https://user-images.githubusercontent.com/47664802/184307578-5efadf31-7eb2-4990-8f4f-cc477e04d6cf.gif)

<br>
![포스트-상세](https://user-images.githubusercontent.com/47664802/184307930-8ac0b24d-bb77-41c3-87a7-d22b0ce0f87d.gif)

<br>

## 8.1 내 역할 -  

<br>

## 8.2 내 역할 - 

<br>

## 8.3 내 역할 - 

<br>


## 9. DB 모델링

<img width="1119" alt="스크린샷 2022-08-12 오후 2 41 28" src="https://user-images.githubusercontent.com/47664802/184291868-638cb04f-b180-40ec-8a93-9a5e95a9f108.png">


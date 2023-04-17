# Django PJT hoIT
---
## 기능목차

### (account)
1. 로그인

2. 로그아웃

3. 회원가입

4. 프로필 수정

### (feed)
5. 피드

6. 게시글 상세보기 -마이페이지,피드

7. 게시글 작성

8. 게시글 수정

---






## 작업 진행 내용(~230416)

(account)
---
1. forms(모델에 필요한 필드를 정의합니다), models, urls, views로 나누어 ...
2. accounts는 유저의 인증과 가입, 로그인, 로그아웃을 구현하는 라이브러리
3. 로그인에 성공한 유저만 게시글 작성 페이지 경로로 연결.
4. 로그인에 성공한 유저만 마이 프로필 경로로 연결시킵니다.

(feed)
---
1. 
2. 
3. 

---
### 필수 구현 기능 등등

1. forms(모델에 필요한 필드를 정의합니다), models, urls, views로 나누어 모듈화.
2. articles는 게시글 작성 페이지, 상세 게시글 페이지, 피드 페이지등 게시글의 CRUD를 구현하는 라이브러리 입니다
3.
---
#### 현재 동작하는 기능들(230416기준)

1. 로그인/로그아웃/회원가입(잘못 적을경우 경고문이 나타납니다.)

2. 글쓰기/마이페이지 이동/유저페이지 이동

3. 수정/삭제

4. 마이페이지 내 그 유저가 쓴 글만 나타남/팔로우/언팔로우

---
#### 230417 추가 작업내역

1. 프로필 수정 기능 추가

2. 프로필,로그인html,css수정(왼쪽위에서 중앙정렬로,그 외 프레임수정)

3. settings.py에서 국가설정(LANGUAGE_CODE = 'ko-kr')수정 'en-us' >> 'ko-kr'

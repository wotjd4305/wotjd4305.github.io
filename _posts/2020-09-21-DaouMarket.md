---
layout: post
title: DaouMarket
tags: [Spring Boot, Vue.js, Jenkins, BootStrap, JPA, Docker,MariaDB, EC2, MVVM, Github]
---
### 중고거래를 손쉽게 하기 위해서 중고거래 사이트를 제작하였고, 동기부여를 위한 포인트, 랭킹, 찜, 채팅을 구현하였습니다. 맡은 역할은 프론트와 백을 둘다 구현하였다.

**기간** : 2020.09 ~ 2020.10

### **맡은 역할**

- **프론트**

```java
# 구성
 - BootStrap을 통한 전체적인 구성.
  제작에 유용한 CSS를 가지고 있는 오픈소스.
 - Vuex라는 상태관리 패턴을 사용
  각 비즈니스 별로 store 파일을 생성, 객체의 상태와 변이를 중앙에서 관리
 - Style Scope 사용
  한 컴퍼넌트(페이지) 마다 Style을 독립적으로 적용

# Input Handling
 - 비밀번호 유효성 체크를 위해 정규 표현식 사용

# 서버 부하방지
 - 디바운싱 사용

# 보안
 - 파일 업로드 시 제한
  jpeg, jpg, png 이외에는 불가능하게(이미지만 필요함으로)
 - 로그인 안한 유저가 다른 페이지 접근 x
  라우터 네비게이션 가드라는 핸들링을 사용, 에상된 서비스 로직 벗어나지 않게 함.

# 비동기적 통신
 - Async&Wait

```

- **백**

```java
# Rest API 제작.
# MyBatis를 이용한 페이징처리, SQL 매핑. 
# 로그인은 JWT 사용.
# 비밀번호 암호화는 SHA256
# 채팅 기능
 - Stomp 프로토콜를 사용.
# 파일 업로드

```



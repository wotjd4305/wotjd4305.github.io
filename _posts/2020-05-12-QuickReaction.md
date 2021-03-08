---
layout: post
title: Quick Reaction
tags: [naver map api, naver geocoding api, firebase deeplink, firebase notification, qr scan, retrofit2(restapi),Github]
---

### 코로나 바이러스와 같은 팬데믹 상황을 해결하기 위해서, 전자방명록을 작성해주는 안드로이드 앱 제작과 무분별한 재난 문자와 출입 명부 개인정보 침해 우려를 해결하고자 하는 프로젝트.

**기간** : 2020.05 ~ 2020.06

### - 맡은 역할
- **자바 안드로이드 앱**

    ```java
    # 사용자 편의를 위한 UI. 액티비티 흐름 구성 UI 구성 및 디자인
    # 서버와의 RestAPI 통신.
    # Mobile Application 각종 기능 구현
     - 맵 트래킹, 지도에 보여주기
      Naver Map API를 통하여 사용자가 방문한 지점과, 움직인 경로 트래킹.
     - 검색어 주소 자동완성
      유저의 디바이스에서 일일이 주소를 다 치는것은 비효율적이고, 형식x
      네이버 지오 코딩 API를 사용해서 검색어 자동완성과 위도 경도 획득.
     - 서버에서 보내주는 QR코드를 인식
      앱이 깔려져있지않으면, FireBase딥링크를 통해 빠른 설치 및 앱으로 이동.
     - 알림 기능
      Firebase의 Notifcation을 사용해서 방문지점에 확진자 발생시 알림 

    # 기본 플로우
    1) 점주는 매장을 등록(사업자번호, 주소)과 관리,
    2) 사용자는 QR스캔을 띄우고 찍음

    ```





---
layout: post
title: "DataBase Project"
tags: [RDS, MYSQL, Github, SPSS, naver trend api, jsoup]
---

### 음원 중 인지도 낮은 가수의 노래가 뒤늦게 화제가 되어 상위권에 머무르는 역주행은 주로 있었지만, 전례없는 역주행으로 논란이 있었기 때문에 조작의심 정도를 판별하는 딥러닝 모델 제작 프로젝트.

**기간** : 2018.09 ~ 2018.12

### - 맡은 역할
- **자료수집 및 데이터 상관관계 파악**

```java
#자료수집 음원 3사의 데이터들을 Jsoup을 이용한 크롤링을 통해 수집 음원의 검색 빈도수를
  - 곡이름, 가수명, 랭킹, 날짜 등

#Naver Trend API를 통해 수집
  - 곡이름으로 얼마나 많은 빈도수가 검색이 되었는지 수집

#데이터 상관관계 분석
 데이터 분석툴(SPSS)에서 데이터를 넣으면 상관관계를 자동으로 나타내줌
 파일의 형식은 CSV파일.
 - 가중치
  [1] 해당 곡 아팉스트의 다른곡이 차트에 진입한 일수
  [2] 차트 진입 후 TOP5까지 진입한 기간
  [3] 음원차트 진입후 5위 이내까지 일간 랭킹 상승 평균치

# RDS 사용.
```

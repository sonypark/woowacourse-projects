# 👨🏻‍💻 woowacourse-projects

<p align="center">
    <img src="./wooteco-cover.jpg" alt="우아한 테크코스 포스터" width="40%" />
</p>



>  [우아한테크코스](https://woowacourse.github.io/)에서 학습한 내용을 정리하는 Repository

<br/>

## 🥚 Level 1 : 프로그래밍 기본

### 기간

- 2020.02.04 ~ 2020.04.10

### 학습 목표

- 자바 프로그래밍 언어에 대한 기본 문법을 익혀 프로그래밍하는 경험을 한다.
- 읽기 좋은 코드를 구현하는 것이 왜 중요한지와 코드를 개선해 읽기 좋은 코드로 변경해 보는 경험을 한다.
- 자신이 구현한 코드에 대해 단위 테스트와 리팩토링하는 경험을 한다.
- 웹 프론트엔드에서 웹 백엔드까지 프로그래밍해 웹 애플리케이션을 개발하는 경험을 한다.

### 진행 미션

|     Project      |                          Repository                          |                         코드 리뷰                         |
| :--------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|  온 보딩 (유닛테스트, 학습테스트)  | [java-calculator](https://github.com/sonypark/java-calculator/tree/onboarding) | [코드 리뷰](https://github.com/woowacourse/java-calculator/pull/53) |
| 자동차 경주 (TDD) |  [java-racingcar](https://github.com/sonypark/mirror-java-racingcar)  | [코드 리뷰](https://github.com/woowacourse/java-racingcar/pull/102) |
|   로또   | [java-lotto](https://github.com/sonypark/java-lotto/tree/manual-lotto) | [코드 리뷰1](https://github.com/woowacourse/java-lotto/pull/147), [코드리뷰2](https://github.com/woowacourse/java-lotto/pull/200) |
|  블랙잭 | [java-blackjack](https://github.com/sonypark/java-blackjack/tree/step2) | [코드 리뷰1](https://github.com/woowacourse/java-blackjack/pull/28), [코드 리뷰2](https://github.com/woowacourse/java-blackjack/pull/107) |
|   콘솔 체스 | [java-chess/step1](https://github.com/sonypark/java-chess/tree/step5) | [코드 리뷰](https://github.com/woowacourse/java-chess/pull/123) |
|   오프라인 코딩 테스트 - 치킨 2020   |            [java-chiken-2020](https://github.com/sonypark/java-chicken-2020/tree/recap-2)            | 코드 리뷰 X: 실력 향상 점검 테스트 |

<br/>

## 🐣 Level 2 : 웹 프로그래밍

### 기간

- 2020.04.21 ~ 2020.06.19

### 학습 목표

- Spring 프레임워크 기반으로 웹 애플리케이션을 개발하는 경험을 한다.
- TDD, ATDD 기반으로 웹 애플리케이션을 개발하고 리팩토링하는 경험을 한다.


### 진행 미션

|       Project        |                          Repository                          |                         코드 리뷰                         |                         비고                         |
| :------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|    웹 체스     | [jwp-chess](https://github.com/sonypark/mirror-jwp-chess) | [코드 리뷰](https://github.com/woowacourse/jwp-chess/pull/71) | 크루 코드 리뷰 |
|   지하철 정보 관리 (인수 테스트)  | [atdd-subway-admin](https://github.com/sonypark/atdd-subway-admin/tree/step4) | [코드 리뷰](https://github.com/woowacourse/atdd-subway-admin/pull/16) | |
|   지하철 경로 조회 (TDD, ETag)   | [atdd-subway-path](https://github.com/sonypark/atdd-subway-path/tree/step3) | [코드 리뷰](https://github.com/woowacourse/atdd-subway-path/pull/7) | |
| 지하철 경로 즐겨찾기 (API 테스트, 문서자동화) | [atdd-subway-favorite](https://github.com/sonypark/atdd-subway-favorite/tree/feat/favorite) | [코드 리뷰](https://github.com/woowacourse/atdd-subway-favorite/pull/25) | |
| todolist 상태 관리 미션 | [todolist](https://github.com/sonypark/todolist/tree/feat/state/sonypark) | [코드 리뷰](https://github.com/woowacourse/todolist/pull/14) | 프론트엔드 선택 미션 ( 순수 js로 상태 관리 패턴 todolist 구현하기) |  

<br/>

## 🐥 Level 3 : 팀 프로젝트

### 기간

- 2020.07.07 ~ 2020.08.28

### 학습 목표

- 개발 프로세스 기반으로 프로젝트 진행, 협업하는 경험을 한다.
- 배포를 자동화하고, 피드백을 받아 지속적으로 개선하는 경험을 한다.

### 진행 프로젝트

|       Project        |                          Repository                          |                         비고                         |
| :------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| [devbie](https://devbie.kr/) | [깃허브](https://github.com/woowacourse-teams/2020-devbie) | [소개 페이지](https://sites.google.com/woowahan.com/wooteco-demo/devbie?authuser=0)

### 담당 작업

- 공고/질문 즐겨찾기, 마이페이지, 공고 상세 페이지, 캐싱 적용(Etag, Spring boot @Cacheable)
- OAuth 로그인, DB 마이그레이션 등 협업


<br/>

## 🐓 Level 4 : 팀 프로젝트 유지 보수 및 웹 백엔드에 깊이를 더하는 단계

### 기간

- 2020.09.08 ~ 2020.11.27

### 학습 목표

- 웹 서버를 직접 구현해 HTTP를 이해하고, 서블릿 컨테이너의 동작 원리를 이해한다.
- JDBC 라이브러리, MVC, DI 프레임워크 구현을 통해 Spring 프레임워크의 동작 원리를 이해한다.
- 레거시 프로젝트를 리팩토링하는 경험을 한다.
- 객체지향 설계, 인증 및 보안, WebSocket 경험을 한다.
- 대용량 서비스를 위한 시스템 아키텍처 설계, 데이터 처리 경험을 한다.

### 진행 미션

|     Project      |                          Repository                          |                         코드 리뷰                         |
| :--------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|  WAS 구현  | [jwp-was](https://github.com/sonypark/jwp-was) | [코드 리뷰](https://github.com/woowacourse/jwp-was/pull/116) |
| 점진적 리펙토링 |  아직 진행 X  | 아직 진행 X  |


<br/>

## 🖋 Writing : 글쓰기 코스

### 진행 미션

| Level |                 Topic                  |                          Repository                          |                         리뷰                         |
| :---: | :------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|   1   |      우아한테크코스 한 달 생활기       | [woowa-writing-2/level1](https://github.com/sonypark/woowa-writing-2/blob/sonypark/%5B%EB%A0%88%EB%B2%A81-%EA%B8%B0%EB%A1%9D%5D%EC%A1%B0%EA%B8%88%20%EB%8A%A6%EC%9C%BC%EB%A9%B4%20%EC%96%B4%EB%95%8C.md) | [리뷰](https://github.com/woowacourse/woowa-writing-2/pull/17) |
|   2   | 우테코에서 찾은 나만의 효과적인 학습법 | [woowa-writing-2/level2](https://github.com/sonypark/woowa-writing-2/blob/sonypark/%5B%EB%A0%88%EB%B2%A82-%EC%84%B1%EC%9E%A5%5D%ED%95%99%EC%8A%B5%EC%97%90%20%EB%8C%80%ED%95%9C%20%ED%83%9C%EB%8F%84.md) | [리뷰](https://github.com/woowacourse/woowa-writing-2/pull/73) |
|   3   |    팀 프로젝트가 나에게 남긴 것     | [woowa-writing-2/level3](https://github.com/sonypark/woowa-writing-2/blob/sonypark/%5B%EB%A0%88%EB%B2%A83-%ED%9A%8C%EA%B3%A0%5D%ED%8C%80%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EA%B0%80%20%EB%82%98%EC%97%90%EA%B2%8C%20%EB%82%A8%EA%B8%B4%20%EA%B2%83.md) | [리뷰](https://github.com/woowacourse/woowa-writing-2/pull/155) |
|   4   |       3기 크루들에게 보내는 편지?       |                       comming soon...                        |                       comming soon...                        |

<br/>

## 기타 활동

### 테코톡: 크루들과 지식을 공유하는 방법

- 발표 주제: 캐싱
- 2020년 9월 16일
- [발표 영상 링크](https://www.youtube.com/watch?v=NxFJ-mJdVNQ&ab_channel=%EC%9A%B0%EC%95%84%ED%95%9CTech)

# :man_technologist: WooJin Choi (elsiff)
`Spring`과 `Java/Kotlin`에 관심이 많고 새로운 기술을 좋아하는 개발자입니다.

> :email: Contact: <elsiff1002@gmail.com>

## :clipboard: Projects
### bistroad
#### :memo: 프로젝트 개요
* 메뉴 설명과 사진, 리뷰 등 자세한 정보를 제공하는 '모바일 메뉴판 플랫폼' 개발을 주제로한 교내 2020 MY캡스톤 프로젝트
* 소비자는 매장 내 `QR코드`를 통해 웹페이지로 메뉴판을 확인하고, 부가적인 앱 설치를 통해 모바일 기기로 `간단한 주문(결제 없이 점주에게 알림)`을 진행할 수 있음
  * 앱 설치 후, 매장에 들어올 때 푸시 알림으로 메뉴판 안내
  * 앱 설치 후, 매장을 나갈 때 푸시 알림으로 리뷰 작성 유도
* 점주는 플랫폼에 자신의 `매장`을 등록하고 관리할 수 있으며, `사용자 리뷰`나 `메뉴 주문 횟수` 등의 사용자 데이터를 수집할 수 있음
* 불특정다수를 위한 온라인 서비스로, 도메인 모델 변경과 트래픽 부하를 사전에 고려하여 설계
#### :date: 진행 기간
* 2020년 7월 ~ 2020년 11월 (진행중)
#### :raising_hand_man: 수행 역할
* 백엔드 서버 개발
#### :hammer_and_wrench: 사용 기술
* Kubernetes와 Docker를 활용한 MSA 구현
* Spring / Spring Boot (Security, Cloud Gateway, Cloud Kubernetes, Data MongoDB)
* Kotlin
* MongoDB
* GCP (GKE, GCB, GCR, GCS)
#### :file_folder: 리포지터리
* https://github.com/Yaneodoo/bistroad-gateway-service
* https://github.com/Yaneodoo/bistroad-user-service
* https://github.com/Yaneodoo/bistroad-store-service
* https://github.com/Yaneodoo/bistroad-order-service
* https://github.com/Yaneodoo/bistroad-review-service
* https://github.com/Yaneodoo/bistroad-auth-service
* https://github.com/Yaneodoo/bistroad-swagger-service
### smart-healthcare
#### :memo: 프로젝트 개요
* 인공지능 동작 인식과 음식 인식을 활용한 '스마트 헬스케어 대사 관리 앱' 개발을 주제로한 교내 2019 산학연계 SW프로젝트
* 건강 정보와 식사, 운동 정보를 기록하고 통계와 같은 피드백 제공
* `대사 관리 기능`: 체중이나 혈압과 같은 사용자 건강 정보 기록 및 BMR, BMI 등의 수치적 피드백 제공
* `식사 관리 기능`: 날짜별로 식사 기록 관리
  * 이미지 인식 기술로 업로드한 사진으로 음식을 추론해내어 사용자 편의성 증대
* `운동 관리 기능`: 날짜별로 운동 기록 관리
  * 동작 인식 기술로 카메라를 통해 실시간으로 사용자의 운동 동작을 인식하여 사용자 편의성 증대
* 그 외에 `그래프 통계`와 `소셜 로그인` 등의 세부 기능 제공
#### :date: 진행 기간
* 2019년 8월 ~ 2020년 5월
#### :raising_hand_man: 수행 역할
* 백엔드 서버 개발
* 웹 프론트엔드 개발
#### :hammer_and_wrench: 사용 기술
* Node.js express
* JavaScript
* MongoDB
* JWT, OAuth2
* Vue.js
* Bootstrap
* AWS (EC2, S3, CodeDeploy)
* Docker와 Nginx를 통한 무중단 배포 환경 구현
#### :file_folder: 리포지터리
* https://github.com/elsiff/smart-healthcare-backend
* https://github.com/elsiff/smart-healthcare-frontend
## :books: Study
### Spring
* [bistroad](https://github.com/elsiff/portfolio#bistroad) 팀 프로젝트 진행을 통해 Spring 프레임워크 실습
  * 프로토타입 개발을 통해 Spring Data JPA 실습
  * 아키텍쳐 변경 이후 Spring Data MongoDB 실습
* [my-todo](https://github.com/elsiff/my-todo) 토이 프로젝트를 통해 WebFlux 기술 실습
* 개인적인 [Spring 정리](https://docs.google.com/document/d/1Lz9Ca13CtYIKkfaKcjmrDAzOoIkfLidUgZ0Kxza8KhI/edit?usp=sharing)를 통해 Spring 구조 파악 및 기초 지식 습득
### Network & Web
* 교내 '컴퓨터 네트워크' 강의로 기초 지식 공부
  * `TIME_WAIT/CLOSE_WAIT`을 발생시키는 Socket 프로그래밍 실습을 통해 TCP 핸드셰이킹 구조 파악과 `close()` 시스템 콜에 대한 중요성 학습
  * Wireshark를 통한 Packet Sniffing 실습을 통해 패킷 암호화에 대한 중요성 학습
* 교내 '데이터베이스' 강의로 Servlet과 JSP에 대한 기초 지식 공부
  * 교내 종합정보서비스 모방 프로젝트를 통해 JSP로 게시판 구현과 이메일/SMS 전송 기능 개발 실습
* 개인적인 [네트워크 & 웹 정리](https://docs.google.com/document/d/1LSv7qkLjnOE8lAZu5mOOG8l0920goMBbJnnqbahe3Z4/edit?usp=sharing)를 통해 기초 지식 복습 및 이해
### Operating System
* 교내 '운영체제' 강의로 기초 지식 공부
* 개인적인 [운영체제 정리](https://docs.google.com/document/d/1LWdCsDp_abuD6ZShF2KqHeCaDxC1vrBG0hF0inU0xCg/edit?usp=sharing)를 통해 기초 지식 복습 및 이해
### Database
* 교내 '데이터베이스' 강의로 기초 지식 공부
  * 교내 종합정보서비스 모방 프로젝트를 통해 ER 다이어그램 작성과 스키마 정규화 실습
* 개인적인 [데이터베이스 정리](https://docs.google.com/document/d/1xPoOrGGuUg6owsJ3KAkLIDog7W9owVkr2sw52me6k8w/edit?usp=sharing)를 통해 기초 지식 복습 및 이해
### Algorithm & Data Structure
* 교내 '자료구조' 강의로 기초 지식 공부
  * 연산자 우선순위가 주어진 계산기 구현 과제를 통해 Stack에 대한 이해와 계산기 구현 전략 습득
* 교내 '알고리즘' 강의로 기초 지식 공부
  * 'The Swapping Puzzle' 과제를 통해 Backtracking 문제 풀이에 대한 전략 습득
* 백준, 프로그래머스 등 온라인 알고리즘 풀이 서비스를 통해 여러 유형의 알고리즘 문제들에 대한 전략 습득
* 개인적인 [알고리즘 & 자료구조 정리](https://docs.google.com/document/d/1r6HoFspymTdsQfB1ufw7Cs7S1IlbCWlytFZCsgSgkuw/edit?usp=sharing)를 통해 기초 지식 복습 및 이해

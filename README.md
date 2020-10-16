# :man_technologist: WooJin Choi (elsiff)
## Projects
### bistroad
#### 프로젝트 개요
* 메뉴 설명과 사진, 리뷰 등 자세한 정보를 제공하는 모바일 메뉴판 플랫폼 개발을 주제로한 교내 2020 MY캡스톤 프로젝트
* 소비자는 매장 내 QR코드를 통해 웹페이지로 메뉴판을 확인하고, 부가적인 앱 설치를 통해 모바일 기기로 간단한 주문(결제 없이 점주에게 알림)을 진행할 수 있음
  * 앱 설치 후, 매장에 들어올 때 푸시 알림으로 메뉴판 안내
  * 앱 설치 후, 매장을 나갈 때 푸시 알림으로 리뷰 작성 유도
* 점주는 플랫폼에 자신의 매장을 등록하고 관리할 수 있으며, 리뷰를 통한 피드백이나 메뉴 주문 횟수 등의 사용자 데이터를 수집할 수 있음
* 불특정다수를 위한 온라인 서비스로, 도메인 모델 변경과 트래픽 부하를 사전에 고려하여 설계
#### 진행 기간
* 2020년 7월 ~ 2020년 11월
#### 수행 역할
* 백엔드 서버 개발
#### 사용 기술
* Kubernetes와 Docker를 활용한 MSA 구현
* Spring / Spring Boot (Security, Cloud Gateway, Cloud Kubernetes, Data MongoDB)
* Kotlin
* MongoDB
* GCP (GKE, GCB, GCR, GCS)
#### 리포지터리
* https://github.com/Yaneodoo/bistroad-gateway-service
* https://github.com/Yaneodoo/bistroad-user-service
* https://github.com/Yaneodoo/bistroad-store-service
* https://github.com/Yaneodoo/bistroad-order-service
* https://github.com/Yaneodoo/bistroad-review-service
* https://github.com/Yaneodoo/bistroad-auth-service
* https://github.com/Yaneodoo/bistroad-swagger-service
### smart-healthcare
#### 프로젝트 개요
* 인공지능 동작 인식과 음식 인식을 활용한 '스마트 헬스케어 대사 관리 앱' 개발을 주제로한 교내 2019 산학연계 SW프로젝트
* 건강 정보와 식사, 운동 정보를 기록하고 통계와 같은 피드백 제공
* 대사 관리 기능: 체중이나 혈압과 같은 사용자 건강 정보 기록 및 BMR, BMI 등의 수치적 피드백 제공
* 식사 관리 기능: 날짜별로 식사 기록 관리
  * 이미지 인식 기술로 업로드한 사진으로 음식을 추론해내어 사용자 편의성 증대
* 운동 관리 기능: 날짜별로 운동 기록 관리
  * 동작 인식 기술로 카메라를 통해 실시간으로 사용자의 운동 동작을 인식하여 사용자 편의성 증대
* 그 외에 그래프 통계와 소셜 로그인 등의 세부 기능 제공
#### 진행 기간
* 2019년 10월 ~ 2020년 5월
#### 수행 역할
* 백엔드 서버 개발
* 웹 프론트엔드 개발
#### 사용 기술
* Node.js express
* JavaScript
* MongoDB
* JWT, OAuth2
* Vue.js
* Bootstrap
* AWS (EC2, S3, CodeDeploy)
* Docker와 Nginx를 통한 무중단 배포 환경 구현
#### 리포지터리
* https://github.com/elsiff/smart-healthcare-backend
* https://github.com/elsiff/smart-healthcare-frontend

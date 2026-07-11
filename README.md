<h1 align="center">👋 Hi, I'm Yunji Han</h1>
<h3 align="center">Backend · AI · Smart Factory Developer</h3>

<p align="center">
  제조·서비스 데이터를 수집하고 처리하여 사용자와 현장에 연결하는 개발자입니다.<br>
  Backend · AI · IoT · Digital Twin을 활용한 시스템 전체 흐름을 설계합니다.
</p>

---

## 🚀 About Me

* 현대오토에버 SW 스쿨 스마트팩토리 과정 수료
* SSAFY 12기 Java 비전공 트랙 수료
* Java / Spring Boot 기반 백엔드 개발
* AI · IoT · 디지털 트윈 기반 스마트팩토리 시스템 개발
* 데이터 수집부터 처리, 저장, 실시간 전달, 시각화까지 전체 시스템 설계 경험
* MQTT, WebSocket, SSE 기반 실시간 데이터 처리 경험

---

## 💻 Tech Stack

### 🖥️ Backend

<p align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MyBatis-000000?style=for-the-badge"/>
</p>

### 🎨 Frontend

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"/>
</p>

### 🤖 AI & Computer Vision

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
</p>

### 🗄️ Database & Cache

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

### 🏭 Real-Time & Digital Twin

<p align="center">
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node--RED-8F0000?style=for-the-badge&logo=nodered&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebSocket-010101?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/SSE-FF6F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white"/>
  <img src="https://img.shields.io/badge/Blueprint-137CBD?style=for-the-badge"/>
</p>

### ☁️ Infra & DevOps

<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
</p>

### 🛠️ Tools

<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>
</p>

---

## 🔥 Projects

### 🏭 Smart Factory Projects

#### 🏭 [Smart Factory MES](https://github.com/HYUNDAI-SW-school-smartfactory/smart-factory-mes)

> 프레스 공정의 생산·설비·알람 데이터를 실시간으로 통합 모니터링하는 MES 대시보드

* 생산량, 달성률, 가동률, 불량률 등 공정 KPI 통합 모니터링
* Spring Boot 스케줄러 기반 5초 주기 생산·설비 데이터 시뮬레이션
* WebSocket을 활용한 설비 상태 및 알람 데이터 실시간 반영
* 공정 흐름, 시간대별 생산량, 설비 상태와 변경 이력 시각화
* Frontend · Backend · Database를 분리한 시스템 구조 및 클라우드 배포

**Tech Stack**
`Java 17` `Spring Boot` `MyBatis` `WebSocket` `MySQL` `Vue.js`

---

#### ⚡ [SCADA Energy Monitoring System](https://github.com/HYUNDAI-SW-school-smartfactory/smart-factory-scada)

> 6개 자동차 사업장의 에너지 사용량과 ESG 운영 지표를 통합 관제하는 Web SCADA 시스템

* 6개 사업장, 24개 주요 공정 설비의 전력·가스·용수·태양광·피크 데이터 생성
* Node-RED에서 생성한 에너지 계측 데이터를 MQTT로 실시간 전송
* Spring Boot MQTT Subscriber에서 데이터를 수신해 MySQL 이력 데이터로 저장
* WebSocket을 활용해 최신 계측 데이터를 Vue 대시보드에 실시간 반영
* 사업장·설비별 에너지 사용량, 피크 전력, 가스·용수 패턴 및 알람 통합 모니터링
* 탄소·용수·태양광·피크·에너지 효율 기반 ESG 등급 산정 및 개선 시뮬레이션 구현

**Tech Stack**
`Java` `Spring Boot` `MyBatis` `MySQL` `MQTT` `WebSocket` `Node-RED` `Vue.js` `SMWP`

---

#### 🚘 [Unreal Engine Digital Twin](https://github.com/HYUNDAI-SW-school-smartfactory/unreal-assembly-digital-twin)

> 제네시스 EV 최종 조립공정과 실시간 생산 데이터를 연동한 Unreal Engine 기반 디지털 트윈

* 동일한 6개 조립공정으로 구성된 3개 생산라인을 독립적으로 구현
* 도어 제거, 라이트 장착, 배터리 팩 장착, 휠·타이어 장착, 도어·시트 장착, 검사·출하 공정 시뮬레이션
* 행거와 차량의 공정 이동, 작업, 배출 및 빈 행거 복귀 흐름 제어
* 로봇팔, AGV, 배터리 리프트, 타이어 조립 셀의 공정별 동작 연동
* Node-RED 생산 데이터를 MQTT로 수신해 가동률, 불량률, 사이클 타임, 생산량을 실시간 반영
* 사이클 타임, 대기열 및 RUN·IDLE 상태를 기반으로 라인별 병목 위치와 원인 시각화
* NORMAL, CYCLE_TIME_BOTTLENECK, IDLE_BOTTLENECK 시나리오 구현

**Tech Stack**
`Unreal Engine 5` `C++` `Blueprint` `MQTT` `Node-RED`

---

#### 📦 [Machine Vision Inventory Inspection](https://github.com/HYUNDAI-SW-school-smartfactory/vision-agv-load-check)

> 미니박스의 라벨을 인식해 재고 수량과 적재 이상 상태를 판별하는 머신비전 시스템

* 원근 변환을 적용해 촬영 각도에 따른 이미지 왜곡 보정
* YOLO를 활용해 미니박스에 부착된 라벨 영역 탐지
* 검출된 라벨 개수를 기반으로 미니박스 재고 수량 산정
* 라벨 위치를 기준으로 개별 미니박스 영역 분리
* 미니박스의 위치와 기울기를 분석해 정상·정렬 불량 상태 판별
* OCR을 활용해 LOT 번호 등 재고 관리 정보 추출

**Tech Stack**
`Python` `OpenCV` `Ultralytics YOLO` `EasyOCR` `NumPy`

---

### 🤖 AI & Computer Vision Project

#### 🚨 [AI Security Blackbox](https://github.com/YunjiHan123/Blackbox)

> 실시간 카메라 영상에서 주거 침입 전조 행동을 탐지하고 증거 화면을 저장하는 AI 보안 시스템

* YOLO 기반 사람·흉기 탐지 및 Pose Keypoint 기반 행동 분석
* 문고리·도어락 조작, 카메라 가림, 얼굴 근접, 배회, 흉기 소지 행동 탐지
* DeepSORT와 Re-ID 모델을 결합해 화면에서 이탈한 사람의 ID 재식별
* 동일 인물의 체류 시간을 누적해 일정 시간 이상 머무르는 배회 행동 판별
* 연속 프레임, 지속 시간, 신뢰도 및 Cooldown 조건을 적용해 일시적인 오탐 방지
* 이상 행동 발생 시 경고와 로그를 출력하고 탐지 시점의 이미지 저장

**Tech Stack**
`Python` `OpenCV` `Ultralytics YOLO` `YOLO Pose` `DeepSORT` `Re-ID` `NumPy`

---

### 💻 SSAFY Projects

#### 🃏 [Pocketing](https://github.com/YunjiHan123/pocketing)

> AI 기반 포토카드 자동 등록 및 교환·거래 플랫폼

* YOLO와 Gemini Vision을 활용한 포토카드 자동 분석
* Spring Boot와 FastAPI를 분리한 AI 연동 구조 구현
* 포토카드 거래, 교환 및 시세 통계 기능 제공

**Tech Stack**
`Java` `Spring Boot` `JPA` `FastAPI` `YOLOv8` `Gemini` `PostgreSQL` `AWS S3`

---

#### 🪖 [똑똑캡](https://github.com/YunjiHan123/smartcap)

> 건설현장의 위험 상황을 실시간으로 감지하는 AI 안전관리 시스템

* YOLO 기반 작업자 및 위험 상황 탐지
* SSE를 활용한 실시간 위험 알림 구현
* Redis Pub/Sub 기반 이벤트 전달 구조 설계
* PostgreSQL과 PostGIS를 활용한 작업자 위치 관리
* AI 분석 지연시간을 3초대에서 1초 미만으로 개선

**Tech Stack**
`Java` `Spring Boot` `FastAPI` `YOLOv11` `Redis` `SSE` `PostgreSQL` `PostGIS`

---

#### 📱 [Moda](https://github.com/YunjiHan123/moda)

> 여러 플랫폼의 콘텐츠를 저장하고 관리하는 개인화 정보 포털

* 유튜브, 블로그, 뉴스 콘텐츠 저장 및 관리
* AI 기반 콘텐츠 요약 기능
* 사용자 및 즐겨찾기 도메인 백엔드 개발
* Android와 Spring Boot 간 API 연동
* 공통 응답 형식 및 API 명세 표준화

**Tech Stack**
`Kotlin` `Android` `Java` `Spring Boot` `MySQL` `Swagger`

---

## 🧩 Baekjoon

<p align="center">
  <a href="https://solved.ac/hyj9908">
    <img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=hyj9908" alt="Solved.ac Profile"/>
  </a>
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/YunjiHan123/YunjiHan123/output/github-contribution-grid-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/YunjiHan123/YunjiHan123/output/github-contribution-grid-snake.svg"
    />
    <img
      alt="GitHub contribution grid snake animation"
      src="https://raw.githubusercontent.com/YunjiHan123/YunjiHan123/output/github-contribution-grid-snake.svg"
    />
  </picture>
</p>

---

## 📫 Contact

<p align="center">
  <a href="mailto:hyj9908@gmail.com">
    <img src="https://img.shields.io/badge/Email-hyj9908%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

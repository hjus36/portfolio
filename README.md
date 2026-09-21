# 📜 이강민 Portfolio

> 이강민(Kangmin Lee)의 개발 프로젝트 및 경험을 정리한 포트폴리오입니다.

<br />

# 👋 Intro

안녕하세요. 컴퓨터공학을 전공하며 **Embedded System, Backend, AI/Data Analysis** 분야를 공부하고 있는 이강민입니다.

STM32 기반 임베디드 시스템과 PCB 설계를 중심으로, Spring Boot 기반 웹 백엔드 개발과 센서 데이터 분석 및 예측 모델 구현까지 다양한 프로젝트를 경험하고 있습니다.

프로젝트에서 실제 문제를 분석하고, 소프트웨어와 하드웨어를 활용하여 해결 방법을 설계하고 구현하는 과정을 중요하게 생각합니다.

<br />

# 🛠 Technical Skills

### Embedded System & Hardware
- **MCU** : STM32H743, ATmega128, Arduino
- **Firmware** : C, STM32 HAL, STM32CubeMX
- **Interface & Control** : GPIO, Timer/PWM, UART, Sensor & Actuator Control
- **Hardware Design** : Schematic Design, PCB Layout & Routing, ERC/DRC Verification

### Backend
- **Language** : Java 17
- **Framework** : Spring Boot 3, Spring Data JPA, Spring Security
- **Database** : MySQL
- **Development** : REST API, JWT Authentication, Gradle
- **Integration** : External API Integration, Mail Service, AI API Integration

### AI / Data Analysis
- **Language** : Python
- **Data Processing** : Pandas, NumPy
- **Machine Learning** : scikit-learn, Prophet
- **Computer Vision** : OpenCV
- **Experience** : Time-series Forecasting, Anomaly Detection, Image Processing

<br />

# 📝 Projects

## 1. ♻️ AI 기반 분리수거 가이드

> **멋쟁이사자처럼 대학 13기 중앙 해커톤 팀 프로젝트**

- **역할** : Backend Developer
- **기술** : Java 17, Spring Boot 3, Spring Data JPA, Spring Security, MySQL
- **주요 경험**
  - Spring Boot 기반 REST API 설계 및 구현
  - 사용자 / 마이페이지 기능 개발
  - 포인트 적립 및 사용 기능 구현
  - GPT 기반 분리배출 퀴즈 생성 및 제출 기능 구현
  - 문의 및 비밀번호 재설정 메일 기능 구현
  - 외부 AI API 연동

AI 이미지 인식과 검색 기능을 활용하여 사용자가 올바른 분리배출 방법을 확인할 수 있도록 지원하는 서비스입니다.

- [Back-end Repository](https://github.com/LIkeLion-Infinite-Loop/backend)
- [Front-end Repository](https://github.com/LIkeLion-Infinite-Loop/frontend)

<br />

---

## 2. 📊 다이나모미터 센서 데이터 분석 및 이상 예측

> **인턴십 프로젝트**

- **분야** : Data Analysis / Machine Learning
- **기술** : Python, Pandas, Prophet
- **주요 경험**
  - 센서 데이터 전처리 및 시간축 정리
  - RPM, Torque, Temperature, Pressure, Vibration 등 센서 데이터 분석
  - 센서 간 관계 및 상관 분석
  - Prophet 기반 단변량 / 다변량 예측
  - 예측 결과를 활용한 이상치 탐지

다이나모미터에서 수집된 센서 데이터를 분석하고, 시계열 예측 모델을 이용하여 상태 변화와 이상 징후를 확인하는 과정을 수행했습니다.

- [Project Repository](https://github.com/hjus36/dynamometer-prophet)

<br />

---

## 3. 🧴 STM32 자동 손세정제

> **대학 교과목 프로젝트**

- **분야** : Embedded System
- **MCU** : STM32H743VIT6
- **기술** : C, STM32CubeMX, GPIO, PWM, Timer
- **Hardware** : IR Sensor, Servo Motor
- **주요 경험**
  - STM32 GPIO 및 Timer 설정
  - IR 센서 입력 처리
  - PWM 기반 Servo Motor 제어
  - 센서 감지에 따른 자동 동작 로직 구현

IR 센서로 사용자의 손을 감지하고 STM32의 PWM 신호로 서보모터를 제어하여 손세정제를 자동으로 배출하는 시스템을 구현했습니다.

<br />

---

## 4. 🔌 STM32H743 / ATmega128 PCB Design

> **대학 교과목 PCB 설계 프로젝트**

- **분야** : Embedded Hardware / PCB
- **MCU** : STM32H743VIT6, ATmega128
- **주요 경험**
  - Schematic 설계
  - PCB Layout 및 Routing
  - 전원 및 신호선 설계
  - ERC / DRC 검증
  - 3D PCB Model 검토

STM32H743 및 ATmega128을 기반으로 회로도 작성부터 PCB 배치·배선, 설계 검증까지 PCB 설계 전 과정을 수행했습니다.

<br />

# 🚧 Projects in Progress

## 5. 🤖 CDP Robot Arm

> **Status : In Progress**

로봇팔을 주제로 진행 중인 CDP 프로젝트입니다.

현재 로봇팔 제어와 Teleoperation 관련 기능을 개발하고 있으며, 데이터 기록 및 재생을 포함한 프로젝트 기능을 확장하고 있습니다.

- [Project Repository](https://github.com/hjus36/cdp)

<br />

---

## 6. 📈 예비캡스톤디자인

> **Status : Planning / In Progress**

재무지표 기반 분석 결과를 하드웨어 장치와 연동하여 보여주는 투자지원 시스템을 설계하고 있습니다.

- Raspberry Pi 기반 분석 서버
- STM32 기반 하드웨어 제어
- 재무지표 기반 종목 분석
- 종목별 투자 비중 LED Bar 표시
- 감열 프린터 결과 출력
- 증권사 API 연동 계획

현재 예비캡스톤 단계로 시스템 구조와 개발 계획을 구체화하고 있습니다.

<br />

# 📞 Contact

- GitHub : [hjus36](https://github.com/hjus36)

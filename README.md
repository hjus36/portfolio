# 📜 이강민 Portfolio

> 이강민(Kangmin Lee)의 개발 프로젝트 및 경험을 정리한 포트폴리오입니다.

<br />

# 👋 Intro

안녕하세요. 컴퓨터공학을 전공하며 **Embedded System & Hardware**를 중심으로 **Backend, AI/Data Analysis** 분야의 프로젝트 경험을 쌓고 있는 이강민입니다.

STM32 기반 펌웨어 제어와 PCB 설계, 3D 기구 설계를 중심으로 하드웨어와 소프트웨어를 직접 연결해 구현해왔으며, Spring Boot 기반 백엔드 개발과 센서 데이터 분석·예측 프로젝트도 수행했습니다.

프로젝트에서 문제를 분석하고, 필요한 기술을 선택해 실제 동작 가능한 결과물로 구현하는 과정을 중요하게 생각합니다.

<br />

# 🛠 Technical Skills

### Embedded System & Hardware
- **MCU** : STM32H743, ATmega128, Arduino
- **Firmware** : C, STM32 HAL
- **Interface & Control** : GPIO, Timer/PWM, UART, Sensor & Actuator Control
- **Hardware Design** : Schematic Design, PCB Layout & Routing, ERC/DRC Verification
- **Mechanical Design** : 3D CAD Modeling, 3D Printing

### Backend
- **Language** : Java
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

### Tools
- **Embedded** : STM32CubeMX, STM32CubeIDE, STM32CubeProgrammer, Microchip Studio
- **Simulation** : Proteus
- **PCB / EDA** : Altium Designer
- **3D CAD** : SOLIDWORKS
- **IDE** : Visual Studio, PyCharm
- **Version Control** : Git, GitHub

<br />

# 📝 Projects

## 1. ♻️ AI 기반 분리수거 가이드

> **멋쟁이사자처럼 대학 13기 중앙 해커톤 팀 프로젝트**

- **역할** : Backend
- **기술** : Java, Spring Boot 3, Spring Data JPA, Spring Security, MySQL
- **주요 구현**
  - Spring Boot 기반 REST API 및 사용자 / 마이페이지 기능
  - 포인트 적립·사용 및 GPT 기반 분리배출 퀴즈
  - 문의 및 비밀번호 재설정 메일 기능
  - 외부 AI API 연동 및 영수증 OCR 인식 기능

AI 이미지 인식과 검색 기능을 활용해 사용자가 올바른 분리배출 방법을 확인할 수 있도록 지원하는 서비스입니다.

- [Back-end Repository](https://github.com/LIkeLion-Infinite-Loop/backend)
- [Front-end Repository](https://github.com/LIkeLion-Infinite-Loop/frontend)
- [시연 영상](https://www.youtube.com/shorts/zPq4j5eChCY)

<br />

---

## 2. 📊 다이나모미터 센서 데이터 분석 및 이상 탐지

> **인턴십 프로젝트**

- **분야** : Data Analysis / Machine Learning
- **기술** : Python, Pandas, NumPy, Prophet
- **주요 수행**
  - 다중 센서 데이터 전처리 및 연속 시간축 구성
  - RPM, Torque, Temperature, Pressure, Vibration 관계 및 상관 분석
  - Prophet 기반 단변량 / 다변량 시계열 예측
  - 진동 데이터 기반 이상치 탐지 및 이벤트 구간 시각화

다이나모미터 센서 데이터를 전처리하고 센서 간 관계를 분석한 뒤, 시계열 예측과 이상치 탐지를 수행했습니다.

- [Project Repository](https://github.com/hjus36/dynamometer-prophet)

<br />

---

## 3. 🧴 STM32 기반 자동 손세정제

> **대학 교과목 임베디드 시스템 프로젝트**

- **분야** : Embedded System / Mechanical Design
- **MCU** : STM32H743VIT6
- **기술** : C, STM32 HAL, GPIO, Timer/PWM
- **구성** : IR Sensor, MG995 Servo Motor, 3D-Printed Gear & Rack Mechanism
- **주요 구현**
  - IR 센서를 이용한 손 감지 및 TIM3 PWM 기반 Servo Motor 제어
  - 1회 자동 분사·복귀 및 반복 분사 방지 로직 구현
  - 기어·랙 기반 기구부 3D CAD 설계 및 3D 프린팅
  - 하드웨어 조립 후 실제 동작 검증

STM32 펌웨어 제어와 직접 설계한 기구부를 결합하여 실제 동작 가능한 자동 손세정제 시스템을 제작했습니다.

- [Project Repository](https://github.com/hjus36/stm32-auto-hand-sanitizer)

<br />

---

## 4. 🔌 STM32H743 / ATmega128 PCB Design

> **대학 교과목 PCB 설계 프로젝트**

- **분야** : Embedded Hardware / PCB Design
- **MCU** : STM32H743VIT6, ATmega128
- **도구** : Altium Designer
- **주요 수행**
  - 데이터시트 기반 Schematic 및 Symbol / Footprint 구성
  - ATmega128 TQFP64, STM32H743 LQFP100 등 주요 Footprint 제작
  - Top / Bottom Layer 기반 2-layer PCB Layout 및 Routing
  - 전원선 폭 구분, GND Polygon / GND Via를 활용한 전원·접지 설계
  - DRC 검증 및 3D PCB Model 기반 기구물 적용 검토

두 MCU 기반 보드를 대상으로 회로도 작성부터 부품 라이브러리 제작, 배치·배선, 설계 검증 및 3D 검토까지 PCB 설계 전 과정을 수행했습니다.

- [Project Repository](https://github.com/hjus36/mcu-pcb-design)

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

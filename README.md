## 🚀 참여 중인 프로젝트

### 1. ASOW (Automatic 3D printing System On the Wall)
* **소속:** 로봇 동아리 CHIRO (상지팀)
* **기간:** 2026.05 ~ 현재
* **기술 스택:** `ROS`
* **요약:** 3D 프린팅 팜 자동화를 위한 벽면 주행 로봇 및 제어 시스템 기획.
* **상세 역할:** * 로봇 제어 미들웨어인 ROS 기반 시스템 아키텍처 스터디 및 설계.
 * 현재 아직 구현 전 단계로, 팀원과 ROS 서적으로 단체 스터디 중.
* **Notion:** [ROS 스터디 노션](https://www.notion.so/ROS2-361cbfed4fd580dba171e6ca32d99b09)

### 2. 비전(Vision) 기반 로봇팔 동적 제어 프로젝트
* **소속:** 창업 동아리 미래제품연구회
* **기간:** 2026.04 ~ 2026.05
* **기술 스택:** `ESP32`, `MicroPython (Thonny)`, `Fusion 360`, `Python`, `OpenCV`
* **요약:** 로봇팔 하드웨어 조립부터 기초 CAD 모델링, 그리고 스마트폰 카메라와 OpenCV를 연동한 객체 탐지 및 물리적 좌표 매핑까지 아우르는 동적 제어 시스템 통합 구현.
* **상세 역할:**
  * **[Hardware & Basic Setup]** 로봇팔 하드웨어 키트 직접 조립 및 ESP32 마이크로컨트롤러 구동 환경 구성.
  * **[CAD Modeling]** Fusion 360을 이용한 기초 3D CAD 모델링 실습을 통해 하드웨어 설계 데이터(Real-world)의 제약사항 이해도 향상.
  * **[Actuator Control]** Thonny IDE를 활용하여 서보모터 구동 및 관절 각도 제어를 위한 MicroPython 소프트웨어 로직 구현.
  * **[Vision Integration]** VS Code 환경에서 OpenCV를 이용해 스마트폰 카메라 영상 데이터 수신 및 객체 탐지 수행. 
  * **[Dynamic Motion]** 계산된 타겟 좌표 데이터를 ESP32로 전송하여 서보모터가 해당 위치로 이동하는 동적 모션 제어 달성.
* **Github:** [로봇팔 제어 Repository]
* **Github:** [로봇팔 제어 코드](https://github.com/shinejihun1227/robotarm)

### 3. 실시간 밴드 합주 애플리케이션 백엔드
* **소속:** 소프트웨어공학 팀 프로젝트
* **기간:** 2026.03 ~ 현재
* **기술 스택:** `Python`, `FastAPI`, `WebSocket`, `GitHub`
* **요약:** 실시간 음원 분석 및 동기화를 지원하는 온라인 밴드 합주 플랫폼 서버 개발.
* **상세 역할:**
  * FastAPI 프레임워크를 활용한 빠르고 안정적인 API 서버 아키텍처 설계.
  * WebSocket을 이용한 실시간 이벤트(드로잉 전파, 동기화 등) 통신 환경 구축.
  * GitHub-flow 브랜치 전략을 도입하여 팀원 간 체계적인 형상 관리 및 코드 리뷰 협업 파이프라인 주도.
* **Github:** [EnsembleSync](https://github.com/rlaalswo1222/EnsembleSync)
* **Notion:** [EnsembleSync](https://www.notion.so/EnsembleSync-44d7bcc855ea8360a7d881ea69f7ad34)

### 4. 임베디드 하드웨어 스터디 (아두이노, 라즈베리파이)
* **소속:** 미래제품연구회, CHIRO
* **기간:** 2026.03 ~ 2026.04
* **기술 스택:** `Arduino`, `Raspberry Pi`, `C++`, `Python`
* **요약:** 하드웨어 제어의 근본 원리를 이해하기 위한 마이크로컨트롤러 및 SBC(Single Board Computer) 학습
* **상세 역할:**
  * **[Arduino]** GPIO 통신 메커니즘을 이해하고, 초음파 센서(거리 측정) 및 L293D 모터 드라이버를 활용한 DC 모터 속도/방향 제어(PWM) 실습.
  * **[Raspberry Pi]**
    - 입력(버튼)과 출력(LED, TM1637)을 통합한 타이머 로직, 하드웨어 자원 예외 처리(Try-Finally) 훈련.
    - I2C 통신(SHTC3, OLED), Telegram API 알림 파이프라인, rpicam 연동 실시간 웹 스트리밍 등 외부 인터페이스 연동 실습.
    - **Github:** [라즈베리파이 실습 코드](https://github.com/exponent1121/raspberrypi-practice)

### 5. 아두이노 기반 라인트레이서 제어
* **소속:** CHIRO
* **기간:** 2026.04 ~ 2026.04
* **기술 스택:** `Arduino`, `C++`
* **요약:** 적외선 센서 데이터를 기반으로 주행 경로를 추적하는 라인트레이서 개발.
* **상세 역할:**
  * IR 센서 피드백을 활용한 DC 모터 방향 및 속도 제어 알고리즘 구현.
* **Github:** [라인트레이서 제어 코드](https://github.com/exponent1121/arduino-line-tracer)
* **시연 영상:** [주행 테스트 영상]
https://github.com/user-attachments/assets/b2f551b6-515d-4947-b27c-dbb5ee2347b2





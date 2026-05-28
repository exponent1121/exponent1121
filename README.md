<img src="https://capsule-render.vercel.app/api?type=waving&color=0:008B8B,50:0ABAB5&height=200&section=header&text=Jisoo+Lim&desc=System%20Engineer&fontSize=40&fontColor=ffffff&descSize=18&descColor=ffffff&descAlignY=50&fontAlignY=30&animation=twinkling" />

## 👩🏻‍💻 Jisoo Lim/Hyunjae
**Aspiring System Engineer | HW/SW Integration & Dynamic Physical Control** <br>
CSE @ Chung-Ang University '24

소프트웨어의 논리가 현실의 하드웨어를 통제하고 움직이게 만드는 **'동적 물리 제어(Dynamic Physical Control)'** 시스템 구축에 몰입하고 있습니다. 

---

### 📬 Contact Me
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:js031121@naver.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jisoo-lim-78b251412/)

---

### 🛠 Tech Stack
**Languages & Frameworks** <br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**Hardware & Embedded** <br>
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-032347?style=for-the-badge&logo=stmicroelectronics&logoColor=white)

**Tools & Vision** <br>
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-F37021?style=for-the-badge&logo=autodesk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

### 🚀 Featured Projects (주요 프로젝트)

#### 🤖 비전(Vision) 기반 로봇팔 동적 제어 시스템 (2026.04 ~ 2026.05)
* **Tech:** `ESP32`, `MicroPython`, `Fusion 360`, `Python`, `OpenCV`
* **Summary:** 스마트폰 카메라와 OpenCV를 연동한 객체 탐지 및 물리적 좌표 매핑을 통한 로봇팔 동적 제어 시스템 통합 구현.
* **Role:**
  * **[Hardware & Setup]** 로봇팔 키트 조립, 기초 3D CAD 모델링(Fusion 360)을 통한 물리적 제약사항 분석 및 ESP32 구동 환경 구성.
  * **[Actuator Control]** Thonny IDE를 활용한 서보모터 구동 및 관절 각도 제어 구현.
  * **[Vision & Dynamic Motion]** OpenCV를 이용한 실시간 객체 탐지 수행 및 타겟 좌표를 ESP32로 전송하여 추적하는 동적 피드백 시스템 구축.
* 🔗 [로봇팔 제어 Repository](https://github.com/exponent1121/robotarm-control)

#### 🏎️ 아두이노 기반 라인트레이서 제어 (2026.04)
* **Tech:** `Arduino`, `C++`
* **Summary:** 적외선(IR) 센서 피드백 데이터를 기반으로 주행 경로를 추적하는 알고리즘 및 DC 모터 제어 구현.
* 🔗 [라인트레이서 제어 코드 Repository](https://github.com/exponent1121/arduino-line-tracer) | 🎥 [주행 테스트 영상](https://github.com/user-attachments/assets/a88eca82-bc36-4d0d-b38e-b1eb2952a67d)

#### 🎬 순수 NumPy 기반 영화 추천 시스템 구현 (2026.05)
* **Tech:** `Python`, `NumPy`, `argparse`
* **Summary:** 외부 딥러닝 프레임워크 없이 순수 선형대수 수식과 NumPy만을 활용하여 유저-아이템 협업 필터링(Biased Matrix Factorization) 알고리즘을 바닥부터 직접 구현 및 최적화.
* **Role:**
  * **[Algorithm Design]** Global, User, Item Bias 및 Latent Factor 행렬 분해 수식을 정의하고, 예측 평점 오버슈팅 방지를 위한 후처리(np.clip) 파이프라인 설계.
  * **[Optimization]** L2 Regularization 패널티 항을 포함한 손실 함수 유도 및 확률적 경사 하강법(SGD)을 적용하여 파라미터 실시간 가중치 업데이트 로직 구현.
  * **[Robustness & Handling]** 미인지 데이터 입력 시 인덱스 범위 조건 검사를 통해 유연하게 대응하는 강력한 Cold-Start 예외 처리 분기 구조 설계.
  * **[Evaluation]** MovieLens-100k 데이터셋 기반의 5-Fold 교차 검증 환경을 구축하고, 하이퍼파라미터 튜닝을 통해 목표 베이스라인인 평균 RMSE 0.9130 돌파(최종 0.912738 달성).
* 🔗 [영화 추천 시스템 Repository](https://github.com/exponent1121/MovieLens-Matrix-Factorization)

---

### 🔥 Currently Working On (진행 중인 프로젝트)

#### 🏭 ASOW (Automatic 3D printing System On the Wall) (2026.05 ~ 현재)
* **Tech:** `ROS`
* **Summary:** 3D 프린팅 팜 자동화를 위한 벽면 주행 로봇 및 제어 시스템 기획.
* **Role:** 로봇 제어 미들웨어인 ROS 기반 시스템 아키텍처 스터디 및 설계 진행 중.
* 🔗 [ROS 스터디 Notion](https://app.notion.com/p/ROS2-361cbfed4fd580dba171e6ca32d99b09)

#### 🎸 실시간 밴드 합주 애플리케이션 백엔드 (2026.03 ~ 현재)
* **Tech:** `Python`, `FastAPI`, `WebSocket`, `GitHub`
* **Summary:** 실시간 음원 분석 및 동기화를 지원하는 온라인 밴드 합주 플랫폼 서버 개발.
* **Role:** FastAPI 기반 안정적인 API 서버 설계 및 WebSocket을 활용한 실시간 이벤트(드로잉 전파, 동기화) 통신 환경 구축.
* 🔗 [EnsembleSync Repository](https://github.com/rlaalswo1222/EnsembleSync) | 🔗 [팀 협업 Notion](https://app.notion.com/p/EnsembleSync-44d7bcc855ea8360a7d881ea69f7ad34?assetsVersion=23.13.20260528.0738)

---

### 📚 Archive & Studies (학습 기록)

#### 💡 임베디드 하드웨어 스터디 (2026.03 ~ 2026.04)
* **Arduino:** GPIO 통신 메커니즘 이해, 초음파 센서 및 L293D 기반 DC 모터 PWM 제어.
* **Raspberry Pi:** 이벤트 기반 타이머 로직 설계, I2C 통신(SHTC3, OLED), Telegram API 파이프라인 및 rpicam 실시간 웹 스트리밍 연동.
* 🔗 [라즈베리파이 실습 코드 Repository](https://github.com/exponent1121/raspberrypi-practice)


<img src="https://capsule-render.vercel.app/api?type=waving&color=0:008B8B,100:0ABAB5&height=120&section=footer" />

# 👋 안녕하세요. 임정민입니다!

> ROS2, STM32, Raspberry Pi, Hailo-8 기반의 **지능형 임베디드 시스템**을 직접 설계하고 개발합니다.  
> 다양한 프로젝트를 통해 하드웨어와 소프트웨어의 융합을 연구하고 있습니다.

--- 
### 🥈 **Smart Gym (운동 자세 분석 시스템)**
> 포즈 인식 + 시퀀스 모델 + EMG 기반 피로도 분석까지 포함한 AI 운동 분석 시스템 

-  YOLOv8-Pose + Hailo-8 Edge AI로 전신 포즈 랜드마크 실시간 추출   
-  TCN 기반 시퀀스 모델로 스쿼트·버피·레그레이즈 등 9종 운동 자동 분류  
-  EMG·IMU 피처 + MLP 모델로 피로도(FI)·불균형(BI) 지표 산출  
-  PySide6 GUI에서 각도·점수·피로도 등 AI 분석 결과 실시간 시각화

📂 Repository: [smart_gym](https://github.com/JeongMinLim-0121/smart_gym)

---

### 🍹 **Vending Machine IoT System (자판기 통합관리)**
> Raspberry Pi · STM32 · Web Server · DB · Bluetooth 기반
 
-  터치 UI로 상품 선택 및 사용자 인터페이스 제공
-  BLE → STM32로 모터 제어 & 판매 요청 전달
-  초음파 센싱으로 배출 성공 여부 자동 판단
-  Web Server + DB로 재고·매출·장애를 실시간 업데이트 및 통합 관리

📂 Repository: [all_vending_machine_unite](https://github.com/JeongMinLim-0121/all_vending_machine_unite)

---

### 🔐 Secure Entry System (출입 인증 제어 시스템) **
> STM32 · GPIO · Interrupt · Timer 기반
 
- 입력 → 인증 → 출력 흐름의 MCU 중심 출입 제어 시스템 구현  
- 인터럽트 기반 입력 처리 및 상태 제어  
- LED·부저를 활용한 인증 결과 시각/음향 피드백  
- 유지보수·확장성을 고려한 펌웨어 구조 설계  

📂 Repository: [Secure Entry System](https://github.com/JeongMinLim-0121/Secure_entry_system)

---
 

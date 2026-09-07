# 사용자 환경에 따른 자동 조절 모니터암



> AI 기반 사용자 인식과 BLE 제어를 활용하여 사용자의 위치와 환경에 맞게 모니터 위치를 조절할 수 있도록 제작한 기계공학 캡스톤디자인 프로젝트입니다.



## Project Overview



- **프로젝트명:** 사용자 환경에 따른 자동 조절 모니터암

- **수행기간:** 2025.03 ~ 2025.06

- **프로젝트 유형:** 기계공학 캡스톤디자인 / 메카트로닉스

- **역할:** 팀장

- **주요 분야:** 기구설계, 모터 제어, BLE 통신, AI Vision 기반 사용자 추적, 시제품 제작



<p align="center">

&#x20; <img src="./01\_overview/project-overview.png" width="700">

</p>



---



## Problem Definition



기존 모니터암은 사용자가 직접 위치와 각도를 조절해야 하기 때문에 거동이 불편한 사용자가 원하는 위치로 반복해서 조작하기 어렵다는 한계가 있습니다.



본 프로젝트에서는 모니터암에 전동 구동부와 사용자 인식 기능을 적용하여 사용자가 직접 모니터를 움직이지 않아도 원하는 위치로 조절할 수 있는 시스템을 제작하는 것을 목표로 했습니다.



---



## Project Goals



- 버튼 및 BLE 기반 모니터암 원격 제어

- 사용자가 설정한 위치 저장 및 자동 복귀

- AI 카메라를 이용한 사용자 얼굴 및 위치 인식

- 사용자 위치 변화에 따른 모니터암 자동 추적

- 다축 구동이 가능한 기계 구조 설계 및 시제품 제작



---



## System Configuration



### Controller



- Orange Board BLE



### Vision



- KOCOAFAB AI CocoCam

- 사용자 얼굴 및 위치 인식

- 인식 결과를 활용한 자동 추적 제어



### Actuator



- HS-7950TH Servo Motor

- MG996R Servo Motor

- LMB2036U Linear Actuator

&#x20; - DC 6V / 12V

&#x20; - 60 N

&#x20; - Stroke 150 mm



### User Interface



- MIT App Inventor 기반 BLE 제어 애플리케이션

- 팀원과 공동 제작



---



## Operating Modes



### 1. Manual Mode



BLE 기반 애플리케이션을 이용하여 사용자가 원하는 방향으로 모니터암을 직접 조작할 수 있도록 구현했습니다.



또한 자동차의 메모리 시트 기능에서 착안하여 사용자가 원하는 모니터 위치를 저장하고, 버튼 입력 시 저장된 위치로 자동 복귀하도록 구현했습니다.



▶ \[Manual Mode Demo](./03\_demo/demo-manual-mode-optimized.mp4)



### 2. Automatic Mode



AI CocoCam을 이용하여 사용자의 얼굴과 위치를 인식하고, 사용자의 위치 변화에 따라 모니터암이 자동으로 이동하도록 제어 로직을 구현했습니다.



사용자가 직접 모니터암을 반복적으로 조작하지 않아도 사용자 위치에 맞춰 모니터가 이동할 수 있도록 구성했습니다.



▶ \[Automatic Mode Demo](./03\_demo/demo-auto-mode-optimized.mp4)



---



## Mechanical Design



모니터암의 구조설계와 3D 모델링은 팀원들과 공동으로 수행했으며, Autodesk Inventor를 활용하여 전체 어셈블리와 구동 구조를 설계했습니다.



### Isometric View



<p align="center">

&#x20; <img src="./02\_design/assembly-isometric-view.png" width="650">

</p>



### Front View



<p align="center">

&#x20; <img src="./02\_design/assembly-front-view.png" width="650">

</p>



### Rear View



<p align="center">

&#x20; <img src="./02\_design/assembly-rear-view.png" width="650">

</p>



### Right View



<p align="center">

&#x20; <img src="./02\_design/assembly-right-view.png" width="650">

</p>



### Section View



<p align="center">

&#x20; <img src="./02\_design/assembly-section-view.png" width="650">

</p>



### Section Right View



<p align="center">

&#x20; <img src="./02\_design/assembly-section-right-view.png" width="650">

</p>



---



## My Contribution



본 프로젝트에서 팀장을 맡아 프로젝트 진행과 업무를 조율했으며, 특히 수동 및 자동 제어 기능 구현을 중심으로 담당했습니다.



- 프로젝트 팀장으로 일정 및 업무 진행 조율

- 수동 및 자동 제어 로직 개발 주도

- Orange Board BLE 기반 모터 구동 제어

- AI CocoCam을 활용한 사용자 인식 및 자동 추적 기능 구현

- 사용자 위치 저장 및 자동 복귀 기능 구현

- MIT App Inventor 기반 BLE 제어 애플리케이션 공동 제작

- Autodesk Inventor 기반 기구설계 및 3D 모델링 공동 수행

- 시제품 제작 및 조립 공동 수행



---



## Technologies / Engineering Skills



- Autodesk Inventor

- Mechanical Design

- Mechatronics

- Orange Board BLE

- BLE Communication

- Servo Motor Control

- Linear Actuator Control

- AI Vision-based User Tracking

- Embedded Control

- MIT App Inventor

- Prototype Development

- Team Project Management



---



## Results



기계 구조설계, 전동 구동부, BLE 통신, AI 기반 사용자 인식을 하나의 시제품으로 구성했습니다.



실제 시제품에서 다음 기능의 작동을 확인했습니다.



- BLE 기반 수동 위치 제어

- 사용자 지정 위치 저장

- 저장 위치 자동 복귀

- AI 카메라 기반 사용자 인식

- 사용자 위치 변화에 따른 자동 추적



---



## Award



### 2025 H-BRIDGE 한남 공학페스티벌



- **종합설계 비IT분야 대상**

- 본 캡스톤디자인 프로젝트를 통해 수상



---



## Related Intellectual Property



본 캡스톤디자인에서 개발한 스마트 모니터암 기술은 프로젝트 종료 후에도 기술을 구체화하고 확장하여 특허 출원 성과로 연결되었습니다.



### 1. 스마트 모니터암 시스템



- **발명의 명칭:** 스마트 모니터암 시스템

- **출원번호:** 10-2026-0049869

- **발명자 참여**



캡스톤디자인에서 개발한 스마트 모니터암의 구조와 제어 개념을 기반으로 기술을 구체화한 특허입니다.



### 2. AI 인식 기반 자율 제어 기능의 지능형 모니터 암



- **발명의 명칭:** AI 인식 기반 자율 제어 기능의 지능형 모니터 암

- **출원번호:** 10-2026-0003663

- **발명자 참여**



스마트 모니터암 기술을 기반으로 추가 인원이 참여하여 개발 범위를 확장했으며, AI 인식을 활용한 사용자 추적 및 자율 제어 기능 등을 추가하여 지능형 모니터암 기술로 발전시켰습니다.



---



## Repository Structure



~~~text

.

├── README.md

├── .gitignore

├── 01\_overview/

│   └── project-overview.png

├── 02\_design/

│   ├── assembly-front-view.png

│   ├── assembly-rear-view.png

│   ├── assembly-right-view.png

│   ├── assembly-section-view.png

│   ├── assembly-section-right-view.png

│   └── assembly-isometric-view.png

├── 03\_demo/

│   ├── demo-auto-mode-optimized.mp4

│   └── demo-manual-mode-optimized.mp4

└── 04\_results/

~~~



---



## Notes



본 Repository는 취업 포트폴리오 목적으로 프로젝트의 설계 과정, 구현 기능, 시제품 및 결과를 정리한 자료입니다.



팀 프로젝트의 결과와 개인 기여 범위를 구분하여 작성하였으며, 프로젝트에서 직접 수행한 업무를 중심으로 정리했습니다.



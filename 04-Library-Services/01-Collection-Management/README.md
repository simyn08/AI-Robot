# 01. Collection Management

## Overview

도서관의 장서관리 업무 중 반복적이고 물리적인 작업을
Physical AI 로봇으로 지원할 수 있는 분야를 정리합니다.

## Library Tasks

### RFID Inventory

RFID를 활용하여 서가의 장서를 자동으로 점검하고
소장자료의 위치 및 상태를 확인합니다.

### Mis-shelved Book Detection

청구기호 및 RFID 정보를 이용하여 잘못 배가된 자료를 탐지합니다.

### Book Sorting

반납된 도서를 청구기호 및 배가 위치에 따라 자동으로 분류합니다.

### Book Transportation

반납도서 및 배가 대상 자료를 서가 또는 작업 공간으로 운반합니다.

### Shelving Support

도서의 정확한 배가 위치를 확인하고 사서의 배가 업무를 지원합니다.

### Automated Shelving

Computer Vision과 Robot Arm을 활용하여
도서를 실제 서가에 자동으로 배가합니다.

## Required Technologies

| Technology | 한국어 | 장서관리에서의 활용 |
|---|---|---|
| **RFID** | 무선주파수인식 | RFID 태그를 이용하여 도서를 식별하고 장서점검, 오배가·분실 자료 탐지 및 위치 확인에 활용 |
| **Autonomous Navigation** | 자율주행 | 로봇이 도서관 내부와 서가 사이를 스스로 이동하며 장서점검, 도서 운반 및 배가 업무를 수행하도록 지원 |
| **Computer Vision** | 컴퓨터 비전 | 카메라 영상을 분석하여 도서, 서가, 청구기호 및 주변 환경을 인식하고 도서 위치 확인과 배가 상태 점검에 활용 |
| **Robot Arm** | 로봇팔 | 도서를 집고 이동하거나 서가에 넣고 꺼내는 작업을 수행하여 도서 정리·배가 업무를 지원 |
| **AI** | 인공지능 | 수집된 정보를 분석하여 도서 식별, 위치 판단, 작업 계획 및 로봇의 자율적인 의사결정을 지원 |
| **Library Management System** | 도서관 관리 시스템 | 소장·대출·반납·도서 위치 등의 도서관 데이터를 로봇과 연계하여 장서 상태 확인 및 자동화된 업무 수행을 지원 |

## Expected Benefits

- 반복적 장서관리 업무 감소
- 장서점검 시간 단축
- 오배가 자료 탐지 효율 향상
- 자료 운반 부담 감소
- 사서의 전문업무 집중 지원

## Related Robot Cases

도서관의 장서점검, 배가, 정리 및 도서 운반 등
장서관리 업무의 자동화를 지원하는 주요 로봇 및 시스템 사례

| Robot / System | Type | Application to Collection Management |
|---|---|---|
| **AuRoSS** | Inventory Robot | RFID 기반 장서점검, 오배가 및 분실 자료 탐지 |
| **Tooker (圖客)** | Shelving Robot | 반납도서 자동 정리 및 서가 배가 지원 |
| **Peanut** | Logistics Robot | 도서 및 자료의 자율 운반을 통한 장서관리 업무 지원 |
| **Oodi Robot System** | Library Automation System | 반납도서 분류·운반 등 도서관 내부 물류 자동화 |
| **Ally BookBot** | Automated Storage System | 도서의 자동 보관·검색·이송을 통한 장서관리 자동화 |

## Research Keywords

`Collection Management`
`RFID Inventory`
`Book Transportation`
`Book Shelving`
`Library Robot`
`Physical AI`

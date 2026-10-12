# 02. Autonomous Navigation

## Overview

도서관 내부에서 로봇이 사람의 조작 없이 이동하고
목적지까지 안전하게 주행하기 위한 기술을 정리합니다.

## Library Applications

- 장서점검 로봇
- 도서운반 로봇
- 이용자 안내 로봇
- 야간 순찰
- 서가 위치 탐색

## Core Technologies

| Technology | Description | Application in Library Robots |
|---|---|---|
| **SLAM** (Simultaneous Localization and Mapping) | 로봇이 주변 환경의 지도를 생성하면서 동시에 자신의 위치를 추정하는 기술 | 도서관 내부 지도를 생성하고 로봇의 현재 위치를 파악하여 자율주행에 활용 |
| **LiDAR** (Light Detection and Ranging) | 레이저를 이용하여 주변 물체와의 거리 및 공간 정보를 측정하는 센서 기술 | 서가, 벽, 이용자 등의 위치를 감지하고 실내 지도 작성 및 장애물 회피에 활용 |
| **Camera** | 영상 정보를 수집하고 컴퓨터 비전 기술을 통해 주변 환경과 객체를 인식하는 장치 | 도서, 서가, 사람, 표지판 등을 인식하고 도서 식별 및 주행 보조에 활용 |
| **Ultrasonic Sensor** | 초음파를 송·수신하여 가까운 물체와의 거리를 측정하는 센서 | 근거리 장애물이나 충돌 위험을 감지하여 안전한 이동을 지원 |
| **Path Planning** | 현재 위치에서 목적지까지 이동할 수 있는 안전하고 효율적인 경로를 계산하는 기술 | 도서관 내부에서 특정 서가, 열람 공간, 대출·반납 장소 등 목적지까지의 이동 경로 생성 |
| **Obstacle Avoidance** | 이동 중 사람이나 물체 등의 장애물을 감지하고 충돌을 피하도록 경로를 조정하는 기술 | 이용자와 이동식 카트 등 동적 장애물이 존재하는 도서관 환경에서 안전한 자율주행 지원 |
| **Indoor Localization** | GPS 사용이 어려운 실내 공간에서 로봇의 위치를 지속적으로 추정하는 기술 | 도서관 내 층, 구역, 서가 등의 위치를 기준으로 로봇의 정확한 위치를 파악하고 이동 및 안내 서비스에 활용 |

## Library Environment Issues

도서관은 일반적인 자율주행 환경과 다른 특징을 가지고 있습니다.

- 좁은 서가 통로
- 이용자의 이동
- 책수레 등 장애물
- 반복적인 서가 구조
- 층간 이동
- 엘리베이터 연동

## Research Questions

- 좁은 서가 사이에서 안정적인 자율주행이 가능한가?
- 이용자와 충돌하지 않기 위한 안전 기준은 무엇인가?
- 도서관 지도와 로봇 위치정보를 어떻게 연계할 수 있는가?

## Keywords

`SLAM` `LiDAR` `AMR`
`Autonomous Navigation` `Path Planning`
`Obstacle Avoidance`

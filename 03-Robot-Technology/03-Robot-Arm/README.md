# 03. Robot Arm

## Overview

로봇이 책을 직접 집고 이동하거나 서가에 배가하기 위한
로봇팔 및 그리퍼 기술을 정리합니다.

## Library Applications

- 도서 파지
- 도서 이동
- 자동 배가
- 반납도서 정리
- 서가정리
- 오배가 도서 이동

## 🤖 Robotic Arm & Manipulation Technologies

| Technology | Korean | Application in Library AI Robots |
|---|---|---|
| **Collaborative Robot Arm** | 협동 로봇팔 | 사람과 같은 공간에서 안전하게 작업하며 도서를 집거나 이동시키는 로봇팔 |
| **Robotic Gripper** | 로봇 그리퍼(집게) | 책을 잡고 놓거나 이동시키는 로봇팔의 말단 장치 |
| **Force Sensor** | 힘 센서 / 힘·토크 센서 | 책을 잡을 때 가해지는 힘을 감지하여 도서 손상을 방지하고 안정적으로 조작 |
| **Motion Planning** | 동작 계획 | 로봇팔이 충돌 없이 목표 위치까지 움직일 수 있도록 동작 경로를 계획 |
| **Object Manipulation** | 객체 조작 | 책을 집고, 이동하고, 원하는 위치에 배치하는 로봇 조작 기술 |
| **Visual Servoing** | 시각 기반 제어 | 카메라의 실시간 영상 정보를 이용하여 로봇팔의 위치와 움직임을 정밀하게 제어 |

## Technical Challenges

도서는 일반적인 산업용 물체와 달리 크기와 두께가 다양하며
서가에 서로 밀착되어 있어 로봇이 한 권만 안정적으로
꺼내거나 삽입하기 어렵습니다.

주요 과제:

- 다양한 크기와 두께의 책
- 책등 인식
- 밀집된 서가에서 한 권만 파지
- 책 손상 방지
- 정확한 위치에 배가
- 높은 서가 접근

## Research Questions

- 책을 손상시키지 않고 어떻게 파지할 것인가?
- 밀집된 서가에서 한 권만 어떻게 꺼낼 것인가?
- 로봇팔의 작업 범위를 어떻게 확대할 것인가?

## Keywords

`Robot Arm` `Gripper` `Book Manipulation`
`Robotic Shelving` `Collaborative Robot`

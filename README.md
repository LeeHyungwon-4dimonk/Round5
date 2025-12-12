# Round5
2D 로그라이크 슈팅 게임으로, 싱글 플레이와 1 대 1 멀티 플레이 대전 기능을 중심으로 시스템을 설계하였습니다.

This repository is a **fork of the original team project**, reorganized for portfolio purposes.

## 시연 영상

https://github.com/user-attachments/assets/975d6508-e9fa-4a3d-9b15-f80440e76925

</br>

## 📌 Project Overview

| 항목 | 내용 |
|------|------|
| **프로젝트 유형** | 팀 프로젝트 (클라 6인) |
| **장르** | 2D Action Roguelike Shooting Game |
| **엔진** | Unity |
| **언어** | C# |
| **개발 방식** | Git + Unity Collaborate, Photon PUN 네트워크 |
| **진행 기간** | *2025-07-22 ~ 2025-08-11* |
| **팀 규모** | *6명* |
| **개인 역할** | 맵/물리 시스템, 로프 시스템, 랜덤 맵 생성 시스템 구현 |

<br>

## 🧑‍💻 Team & Roles

| 이름 | 역할 |
|------|------|
| **엄신원 (HugeChamChi)** | 캐릭터 + 네트워크 담당 |
| **송덕원 (Rio-Song-kr)** | 이펙트 시스템 |
| **이형원 (LeeHyungwon-4dimonk)** | 맵/물리 시스템, 랜덤 맵 생성, 로프 시스템 |
| **김동진 (GBron)** | 이펙트 시스템 |
| **조기훈 (PHSTD)** | 무기 시스템 |
| **권용호 (YongHo-FOG)** | 카드 시스템 | :contentReference[oaicite:0]{index=0}

<br>

## 🧑‍💻 My Contributions

### 🎯 Gameplay & Core Systems
- 온라인 대전용 맵 5종 디자인 및 구현
- 오브젝트 물리 엔진 설계 및 Photon 기반 네트워크 동기화
- 플레이어 360도 팔 회전 애니메이션 구현

### 🎨 Visual & FX
- DoTween을 활용한 맵 전환 및 UI 연출
- 셰이더 & 포스트 프로세싱을 통한 캐릭터/맵 비주얼 작업

### 🧱 Level & Environment Design
- 전투 흐름을 고려한 맵 구조/지형 설계
- 상호작용 오브젝트 및 레벨 기믹 제작

<br>

## 🛠 Tech Stack

### ✔ Core
- Unity (C#)
- Photon Unity Networking (PUN) for multiplayer

### ✔ Tools
- Git / GitHub
- Custom shaders & sprite tools

</br>

## 📁 My Code Overview

하기 경로에 제가 직접 구현한 스크립트들이 정리되어 있습니다.

Assets/LHW/Scripts/

### 🔹 랜덤 맵 생성 및 이동 연출 시스템
- RandomMapPresetCreator.cs
- MapController.cs

📂 Path: `Assets/LHW/Scripts/GameSystem/MapSystem/`

### 🔹 Joint 기반 맵 오브젝트 물리 시스템 & 로프 시스템
- BoxController.cs
- RopeCreator.cs

📂 Path: `Assets/LHW/Scripts/Map`

📂 Path: `Assets/LHW/Scripts/Objects/Rope/RopeCreator/`

### 🔹 DoTween 활용 UI 연출
- IngameUIManager.cs
- RoundOverPanelController.cs

📂 Path: `Assets/LHW/Scripts/GameSystem/UI/`

### 🔹 커스텀 셰이더
- LeftCharacter.shadergraph
- PlatformMaterialShader.shadergraph

📂 Path: `Assets/LHW/Material/Character`

📂 Path: `Assets/LHW/Material/Platform`

### 🔹 Spline 활용 팔 애니메이션
- CardSceneCharacterLeftArm.cs

📂 Path: `Assets/LHW/Scripts/CardAnimation/`


## 📦 How to Run

1. Repository를 클론합니다.  
2. Unity 2022.6 이상으로 프로젝트를 엽니다.  
3. Photon App ID를 설정한 후 Play를 누르면 실행됩니다.

* 회원가입을 진행하면 접속할 수 있으며, 별도의 이메일 인증 없이 이메일 형식만 지킨 테스트 이메일로 생성할 수 있습니다.

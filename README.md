
# 🚗 전국 휴게소 맛집 및 여정 정보 큐레이션 시스템  
### Flask 기반 웹 서비스 프로젝트

전국 고속도로 **휴게소 맛집 정보**와 **이동 여정 경로**를 한눈에 제공하는 웹 서비스입니다.  
사용자의 출발지–도착지 흐름에 따라 **경로상 휴게소를 자동 탐색**하고,  
맛집·편의시설 정보를 **직관적인 지도 UI**로 큐레이션하는 것을 목표로 개발했습니다.

---

## 📌 프로젝트 개요

- **프로젝트명**: 전국 휴게소 맛집 및 여정 정보 큐레이션 시스템  
- **개발 기간**: 2025.12 
- **개발 인원**: 5명  
- **역할**:  
  - 기술 아키텍처 설계 (PL)  
  - Flask 백엔드 핵심 로직 개발  
  - REST API 설계 및 데이터 흐름 구조화  

---

## 🛠 기술 스택

### Backend
- Python
- Flask
- SQLite

### Frontend
- HTML / CSS / JavaScript
- Google Maps JavaScript API

### 기타
- REST API
- Git / GitHub
- JSON 데이터 처리

---

## 🚀 주요 기능

- 🔍 **출발지–도착지 기반 경로 탐색**
- 🛣 **경로상 휴게소 자동 추출**
- 🍜 **휴게소별 맛집 정보 제공**
- ⛽ **편의시설(주유소, EV 충전소 등) 아이콘 표시**
- ⭐ **사용자 친화적인 카카오 API를 활용한 지도 기반 UI**

---

## 🧠 시스템 흐름

1. 사용자가 출발지와 도착지를 입력  
2. Google Maps API를 통해 이동 경로 계산  
3. 경로 좌표 기반으로 인근 휴게소 필터링  
4. 휴게소별 맛집·시설 데이터 매칭  
5. 지도 및 리스트 형태로 결과 출력  

---

## 📊 프로젝트 발표 자료

🔗 [**Google Slides 발표 자료 바로가기** ](https://docs.google.com/presentation/d/e/2PACX-1vTkiAo32hMr4zrigNEaB6z2tsfOwmbTQcUz23JqTGH18wYwzV1yfw0ZCI4Hw8V8hw/pubembed?start=false&loop=false&delayms=3000)

---

## 📂 프로젝트 구조

```bash
FLASK_PROJECT/
┣ static/
┃ ┣ css/
┃ ┣ js/
┣ templates/
┃ ┗ index.html
┣ app.py
┣ requirements.txt
┗ README.md
'''
---
## ⚙ 실행 방법

```bash
# 가상환경 생성
python -m venv venv

# 가상환경 활성화 (Windows)
venv\Scripts\activate

# 패키지 설치
pip install -r requirements.txt

# 서버 실행
python app.py
'''

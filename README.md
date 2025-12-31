
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


## 🛠 기술 스택 (Tech Stack)

### Environment
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

### Data & Machine Learning
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Visualization
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-4458ad?style=for-the-badge&logoColor=white)

### Deployment
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)


---

## 🚀 주요 기능

- 🔍 **출발지–도착지 기반 경로 탐색**
- 🛣 **경로상 휴게소 자동 추출**
- 🍜 **휴게소별 맛집 정보 제공**
- ⛽ **편의시설(주유소, EV 충전소 등) 아이콘 표시**
- ⭐ **사용자 친화적인 카카오 API를 활용한 지도 기반 UI**

---

## 📢 시스템 흐름

1. 사용자가 출발지와 도착지를 입력  
2. Google Maps API를 통해 이동 경로 계산  
3. 경로 좌표 기반으로 인근 휴게소 필터링  
4. 휴게소별 맛집·시설 데이터 매칭  
5. 지도 및 리스트 형태로 결과 출력  

---

## 📊 프로젝트 발표 자료

💛 [**Google Slides 발표 자료 바로가기** ](https://docs.google.com/presentation/d/e/2PACX-1vTkiAo32hMr4zrigNEaB6z2tsfOwmbTQcUz23JqTGH18wYwzV1yfw0ZCI4Hw8V8hw/pubembed?start=false&loop=false&delayms=3000)

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
```
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
```

---
##✨ 기대 효과

- 장거리 운전자에게 **실질적인 휴게소 선택 기준 제공**
- 지도 기반 UX로 **정보 탐색 피로도 감소**
- 향후 사용자 리뷰·추천 알고리즘 확장 가능

---
##📎 향후 개선 사항

- 사용자 리뷰 및 평점 기능 추가
- 로그인 기반 개인화 추천
- 모바일 반응형 UI 개선
- Streamlit 또는 React 기반 확장

  ---
  
## 🎬 서비스 시연 영상
[https://github.com/minseo3280-coder/Flask_project/issues/1#issue-3769423576](https://private-user-images.githubusercontent.com/248983211/530920997-0e13a852-d974-45ea-abad-3a617695d5e6.mp4?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjcwODI4MDMsIm5iZiI6MTc2NzA4MjUwMywicGF0aCI6Ii8yNDg5ODMyMTEvNTMwOTIwOTk3LTBlMTNhODUyLWQ5NzQtNDVlYS1hYmFkLTNhNjE3Njk1ZDVlNi5tcDQ_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUxMjMwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MTIzMFQwODE1MDNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZDkxMGE2YmM4NmU0MWZmMzZmYWMzNTg2ZDA2NjMyMTk3Yzg1NDFkOTYwYWZmMTA3MTQ2YzI0OWQyZDFkYWM1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.fmQvu3c2Wfi_NjkMx8U17vH5XcRf8c_CLJOuFKA-D6g)


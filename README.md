# BA_Project01
외래 관광객의 국내 방문 사유와 재방문율 분석

## 📅 일정
총기간 : 2023. 06. 08 ~ 2023. 06. 19

<br>

## 📌 목표

1. 데이터 분석

<br>

## 📖 상세 내용

- 입국객 특성 변수를 활용해 입국 추이, 방문 목적, 만족도 분석
- 특정 변수별로 입국객 소비 패턴을 분석해 높은 소비율을 보이는 특성 분석
- 재방문객의 특성을 분석해 어떤 사람이 재방문을 할지 RFM분석
- 우리나라 관광사업의 SWOT
- 설문조사 데이터의 한계점

<br>

## 🐰 역할

- 팀장
- 일정 관리 및 기획
- 전처리 의사결정
- 데이터 가공 의사결정
- 재방문시 소비패턴 시각화 및 인사이트 도출
- 코드 개발 컨설팅
- 발표

<br>

## 🛠️ Stack
|분야|사용 기술|
|------|---|
|Data Preprocessing|<img src="https://img.shields.io/badge/numpy-색상?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/pnadas-색상?style=for-the-badge&logoColor=white">|
|Plot|<img src="https://img.shields.io/badge/matplotlib-색상?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/seaborn-색상?style=for-the-badge&logoColor=white">|
|Analysis|<img src="https://img.shields.io/badge/RFM-색상?style=for-the-badge&logoColor=white">|
|MS|<img src="https://img.shields.io/badge/Excel-색상?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/PPT-색상?style=for-the-badge&logoColor=white">|
|Share|<img src="https://img.shields.io/badge/Google Drive-색상?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/Notion-색상?style=for-the-badge&logoColor=white">|

<br>

## 🔥 성장경험

<br>

## ✨ 문제점 및 해결

😒 졸음쉼터 이용률 데이터는 **없음**

1. 어떤 데이터로 유추할 수 있을까❔
    
    👉 고속도로 이용량과 졸음쉼터 설문조사, 졸음쉼터 주변 교통사고량을 이용해 이용량 유추
    
<br>

😒 데이터 만으로는 연관성을 읽어내기 **어려움**

1. 위경도와 단순 수치(예, 이용률, 사고율)로만 표기
    
    👉 지도 시각화로 주변 사물과의 거리 확인 → 외부 환경 요소 확인
    
    👉 지도 시각화로 지리적 특성 확인
    
    ➖ 터널 데이터, 휴게소 데이터 추가적으로 수집
    
<br>

😒 ‘졸음’이라는 기준이 **모호**

1. 원인은❔
    
    ➖ 실험 대상자가 ‘졸음’이라고 인지해야 졸음으로 표기
    
    ➖ 기존 data의 Target변수의 범주가 {1: 정상, 2:졸음, 3:수면}
    
    👉 졸음을 제거 후 {1: 정상, 3:수면}으로 모델링을 진행하였고 정확도가 향상됨
    
<br>

## ✨ 한계점

- 설문데이터임으로 “허위응답”이 존재하기마련이고, 분석결과의 신뢰도를 떨어트릴 수 있어 공신력 있는 자료(뉴스, 논문 등) 내용 / 데이터 분석 내용 / 데이터 값을 비교해가며 결론을 내려야 했다.
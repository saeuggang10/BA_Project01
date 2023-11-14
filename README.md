# BA_Project01
외래관광객 특성에서 유의미한 인사이트를 도출하여 재방문율을 높이기 위한 방안 탐색

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
- 각 팀원의 강점을 살려 팀 내에서의 역할 및 책임을 적절히 분배하고, 팀원들이 자신의 의견을 표현하고 발전시킬 수 있는 기회를 제공
- RFM 분석을 통해 얻은 결과를 기반으로 재방문객을 찾기 위한 데이터 기반 의사결정에 도전. 재방문객의 특성을 찾아 그에 맞는 마케팅 전략을 수립하고자함

<br>

## ✨ 문제점 및 해결

😒 3년 간에 질문과 응답 항목이 각기 다르게 구성됨

1. 어떤 기준으로 파일을 통합해야 할까❔
    
    ➖ 설문조사는 응답률을 높이거나, 거짓응답을 줄이기 위하여 매년 질문 형식을 바꾸거나, 응답 항목 내용을 바꿈
    
    ➖ 따라서 최근 년도일수록 가장 현재와 유사한 트렌드에 관련된 질문이며, 응답률을 높이기 위해 고심된 질문일 것으로 생각됨
    
    👉 가장 최근 년도의 설문지(2019년도)의 항목에 맞춰 파일 병합

   <br>
    
2. 두 개였던 항목이 하나가 되었을 때
    
    ➖ 예, 2017년도 → 5번, 뷰티/의료관광
   <br>
       2019년도 → 5번, 뷰티관광   6번, 의료관광
    
    👉 뷰티 : 의료 = 8 : 2로 있다면 2017년 데이터 값을 8 : 2로 랜덤하게 나눔
    

   <br>
    
3. 항목이 사라졌을 때
    
    ➖ 예, 2018년도 → 3번, 고궁유적방문
   <br>
      2019년도 → 유사항목없음
    
    👉 기타 항목을 만들어 넣음
    
<br>

## ✨ 한계점

- **설문**데이터임으로 “**허위응답**”이 존재하기마련이고, 분석결과의 신뢰도를 떨어트릴 수 있음
    
    👉 실제 알려진(뉴스, 논문 등) 내용과 데이터 분석 내용을 비교하여 결론내림

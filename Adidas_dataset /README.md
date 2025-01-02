# Adidas 구매 데이터 분석

## 1. 프로젝트 개요
<img src="https://github.com/user-attachments/assets/fa2e2dc4-552c-46eb-8106-b7bb8c8ffadf" width="500" height="300"/>

[Kaggle의 Adidas 데이터셋](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset) 분석 프로젝트입니다. 데이터 전처리, 탐색적 데이터 분석(EDA)을 통한 판매 경로에 따른 매출량 분석과 영업이익 및 판매단가의 추이를 파악하여 마케팅 전략을 도출합니다. 
이 프로젝트의 목표는 고객 데이터의 분포를 분석하여 주요 특징을 도출하고, 이를 바탕으로 마케팅 전략을 제시하는 것입니다. 

## 2. 데이터 설명
- 데이터 출처 : [Kaggle의 Adidas 데이터셋](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset)
- 데이터 상세 : 칼럼 13 개, 데이터 9648 행
  - Retailer : adidas 브랜드를 판매하는 유통처
  - Retailer ID : 판매점 ID
  - Product : 제품 카테고리
  - Price per Unit : 상품 1개당 가격
  - Units Sold : 판매수량
  - Total Sales : 판매금액
  - Operating Profit : 영업이익(매출액 - 원가)
  - Operating Margin : 영업마진(영업이익율)
  - Sales Method : 판매 방법

## 3. 분석 과정
1. 데이터 전처리
   - regex로 특수문자 제거
   - 데이터타입 변환
   - 결측치 제거
     
2. 탐색적 데이터 분석(EDA)
     - 월별 판매량 분석
     - 마진율 분석
     - 판매방법에 따른 마진율/판매단가 분석
     - 판매방법에 따른 판매성과 분석
     - p-value를 통한 통계적 유의성 판단
       
4. 마케팅 전략 도출
   
## 4. 필요한 라이브러리
- pandas
- numpy
- plotly
- statsmodels

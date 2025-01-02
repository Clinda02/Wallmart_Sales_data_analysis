# Indian E-commerce 데이터 분석 및 대시보드 구축

## 1. 프로젝트 개요
<img src="https://github.com/user-attachments/assets/26897f67-ae2b-4ca7-846c-3a511c8b9451" width="800" height="200"/>

[Kaggle의 E-commerce 데이터셋](https://www.kaggle.com/datasets/benroshan/ecommerce-data?select=List+of+Orders.csv) 분석 프로젝트입니다. 데이터 전처리, 탐색적 데이터 분석(EDA)을 통한 데이터의 분포를 확인하고, 월별/지역별/카테고리별 구매고객 특징을 파악하여 마케팅 전략을 도출합니다.  
이 프로젝트의 목표는 Streamlit을 활용한 시각화 대시보드를 구축해 실시간으로 e-commerce 구매 데이터의 추이량을 파악하고, 이를 바탕으로 마케팅 전략을 제시하는 것입니다. 

## 2. 데이터 설명
- 데이터 출처 : [Kaggle의 E-commerce 데이터셋](https://www.kaggle.com/datasets/benroshan/ecommerce-data?select=List+of+Orders.csv)
- 데이터 개요 : 테이블 2개과 칼럼 11개, 데이터 로우 수 2,060 건.
  - List of Orders : 주문 데이터. 주문ID, 주문날짜, 고객명, 도시 등 지역 정보.
  - Order Details : 주문 상세 데이터. 주문ID, 판매가격, 수익, 수량, 카테고리, 세부 카테고리 정보.

## 3. 분석 과정
1. 데이터 전처리
     - 결측치 제거
2. 탐색적 데이터 분석(EDA)
     - 주요 통계 지표 확인
     - 각 변수의 분포 시각화
3. 대시보드 구축 
   - Streamlit을 활용한 동적 대시보드 구현
    1) 월별 판매량 분석
       - 월별 판매량 추이 분석
       - 월별 매출액 추이 분석

    2) 품목별 판매량 분석
       - 카테고리별 판매량 분석
       - 월별/카테고리별 누적 판매량 분석
      
    3) 지역별 주력 판매상품
       - 지역별/카테고리별 주문수량 히트맵 분석
       - 지역별/카테고리별 주문금액 히트맵 분석

## 4. 필요한 라이브러리
- pandas
- numpy
- plotly
- streamlit

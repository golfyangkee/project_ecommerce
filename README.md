# Adidas data
캐글의 아디다스 판매 데이터를 가지고  
데이터 전처리 및 분석 진행
- 판매 방법에 따른 판매성과에 차이가 있을지에 대해 ANOVA(분산분석) 사용
- 최소자승법(OLS, Ordinary Least Squares) 으로 선형회귀 모델 만듦
## 결론
1. 판매방법에 따라 단가 차이가 있다. In-store > On-line > Outlet 순
2. 판매방법에 따라 마진율(이익율) 차이가 있다. On-line > Outlet > In-Store 순

   
# E-commerse data
캐글의 Olist 테이블과 detail 테이블을 가져와서 조인해보고
데이터 전처리 및 분석 진행 후 시각화 및 대시보드 만들기
- plotly로 시각화
- streamlit 으로 웹 어플리케이션 구현
## 결론
1. 전체 주문량 및 판매금액 증가
2. 카테고리별 분석 결과 전체 카테고리 주문량 증가
3. 지역별 주력상품 확인

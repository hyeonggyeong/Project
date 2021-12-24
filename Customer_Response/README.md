# Customer_Response_Predict 
 1. 데이터 전처리
 2. EDA
 3. 고객반응(이벤트참여여부) 예측 (SVM ,RandomForest)

ID: 고객ID
Year_Birth: 고객 생년월일
Education: 고객의 교육수준
Marital_Status: 고객의 결혼여부
Income: 고객의 연간 가구소득
Kidhome: 고객의 가구 내 자녀의 수
Teenhome: 고객의 가구 내 청소년 수
Dt_Customer: 고객이 회사에 등록한 날짜(회원가입 일자)
Recency: 고객의 마지막 구매 후 지난 일수 
Complain: 지난 2년동안 고객 불만 제기한 경우 1, 그렇지 않을 경우 0

MntWines: 지난 2년 간 와인 소비량
MntFruits: 지난 2년 간 과일 소비량
MntMeatProducts: 지난 2년 간 육류 소비량
MntFishProducts: 지난 2년 간 생선 소비량
MntSweetProducts: 지난 2년 간 간식 소비량
MntGoldProds: 지난 2년 간 금 소비량

NumDealsPurchases: 할인제품 구매 건 수
AcceptedCmp1: 첫 번째 할인 이벤트에서 고객이 구매한 경우 1, 그렇지 않은 경우 0
AcceptedCmp2: 두 번째 할인 이벤트에서 고객이 구매한 경우 1, 그렇지 않은 경우 0
AcceptedCmp3: 세 번째 할인 이벤트에서 고객이 구매한 경우 1, 그렇지 않은 경우 0
AcceptedCmp4: 네 번째 할인 이벤트에서 고객이 구매한 경우 1, 그렇지 않은 경우 0
AcceptedCmp5: 다섯 번째 할인 이벤트에서 고객이 구매한 경우 1, 그렇지 않은 경우 0
Response: 지난 이벤트에서 고객이 구매한 경우 1, 그렇지 않은 경우 0

NumWebPurchases: 웹사이트를 통한 구매 건 수
NumCatalogPurchases: 카탈로그를 통한 구매 건 수
NumStorePurchases: 매장에서 직접 구매한 건 수
NumWebVisitsMonth: 지난 달 회사 웹 사이트 방문 수

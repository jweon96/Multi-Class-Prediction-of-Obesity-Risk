# Multi-Class-Prediction-of-Obesity-Risk

### 프로젝트 소개
- 본 프로젝트는 개인의 비만 위험을 예측하기 위해 LightGBM, XGBoost, Gradient Boosting, RandomForest 등의 머신러닝 기법을 사용합니다. 학습 데이터셋을 기반으로 모델을 개발하고, 이를 통해 생성된 모델로 Kaggle 대회에 결과를 제출합니다.

---
### 팀원 소개
1. [dsmondo](https://github.com/dsmondo)
2. [jweon96](https://github.com/jweon96)
3. [JiHoonYoon00](https://github.com/JiHoonYoon00)
---
### 데이터셋 출처
- [Kaggle](https://www.kaggle.com/competitions/playground-series-s4e2/data)
- [Kaggle](https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster)
---
### Train.csv 주요 칼럼
- Weight : 39 ~ 165 몸무게
- family_history_with_overweight : 과체중 가족력
- FAVC : 열량이 높은 음식의 섭취 빈도
- FCVC : 채소 섭취 빈도
- NCP :주식수
- CAEC :식사 간 음식 섭취
- CH2O : 1일 물 섭취량
- SCC : 칼로리 소모량 모니터링
- FAF : 신체활동 빈도
- TUE : 전자 기기 사용 시간
- CALC : 알코올 섭취량
- MTRANS : 교통수단 이용
- NObeyesdad : 체형
---
### 구조
```
├── data # 데이터 분석에 사용되는 데이터셋 폴더
│ ├── Train.csv # 머신러닝 학습용 데이터
│ ├── Test.csv # 머신러닝 테스트용 데이터
│ ├── sample_submission.csv # 최종 제출 샘플용 데이터
│ ├── ObesityDataset.csv # 원본 데이터
│ 
├── images # 이미지 폴더
│ ├── FlowChart.png
│   
├── obesity_risk_beginner.ipynb # 프로젝트 코드 실행
│ 
├── requirements.txt # 필요한 파이썬 패키지 목록
└── README.md # 프로젝트 설명 파일
```
---
###  머신러닝
- **LightGBM** 
- **XGBoost** 
- **Gradient Boosting** 
- **RandomForest** 
---
### 라이브러리 소개(requirements.txt)
#### 데이터 전처리      
- **pandas==1.5.3**
- **numpy==1.26.3**
#### 시각화
- **matplotlib==3.6.0**
- **Seaborn==0.13.2**
#### 머신러닝
- **lightgbm==4.3.0**
- **xgboost==2.0.3**
- **scikit-learn==1.2.2**
---
### Flow Chart
- 아래는 플로우 차트를 보여주는 다이어그램입니다.
<img src="https://github.com/JiHoonYoon00/Multi-Class-Prediction-of-Obesity-Risk/blob/main/images/FlowChart.png"/>

---
<p align="center">
   <img src="https://img.shields.io/badge/language-python-blue?style"/>
</p>


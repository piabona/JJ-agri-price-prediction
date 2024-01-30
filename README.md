
## Dacon 제주 특산물 가격 예측 AI 경진대회

- 대회 개요 https://dacon.io/competitions/official/236176/overview/description
- 2023 11월 제주 특산물 가격 예측 AI 경진대회 (public 64등/1093팀, private 288등/1093팀)

## Summary
- **Data Selection** : 상품별 모델링 (품목-지역-법인 의 조합)
- **Feature Engineering** : 주로 시간(요일, 월) 파생변수 및 기간별 price와 supply의 mean/std/max 등을 추가
- **Model** : Autogluon Timeseries Predictor
- **Refinement** : Prediction 분위수 (0.1~1.0)를 개별 활용하여 (0.4~0.6) 최종 예측 

## Environment
- OS: Ubuntu 18.04.4 LTS (GNU/Linux 4.15.0-162-generic x86_64)
- Environment: Anaconda 4.10.3

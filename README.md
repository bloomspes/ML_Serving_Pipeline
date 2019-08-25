# ML_Serving_Pipeline
## Machine Learning Serving Pipeline 구축
**[요구사항]**
1. Serverless API(Google Functions, Azure Functions, AWS Lambda)로 머신러닝 모델 CPU 서빙
2. 데이터셋은 Google BigQuery에 적재하고 꺼내서 사용
3. 학습 실험 관리 Opensource(Microsoft NNI, Google Adanet, Optuna 등)를 사용하여 AutoML 수행
4. 학습이 완료되면 Model Validation을 자동으로 수행해서 지금 서빙되고 있는 모델보다 우수한지 자동으로 검증
5. 모델리스트가 관리되어야 하고, 선택적으로 배포 및 롤백이 가능함
6. 모든 코드는 Pylint 가이드에 맞춰 깔끔함을 유지 (PEP8, Google Style 등) 
7. 서빙할 딥러닝 모델은 상관없음. MNIST, 얼굴 인식, Object Detection

- 문제 푸는 기간: 2주
- 문제 제출 마감: 2019-09-08 14:00:00 (GMT+9)

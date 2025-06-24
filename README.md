<h1>Quality Prediction for KorensEM Motor Production</h1>

<h2>개발 내용</h2>
Motor 공정은 여러 개의 중간 공정을 거치며, 각 공정의 중간에 품질 검사를 수행

![image](https://github.com/user-attachments/assets/2685e4a6-8395-4f90-bb74-e6364e2996f0)

이 중 주요 조립 공정에 속하는 OPM90의 공정 데이터를 활용하여 품질 예측 모델을 개발, 2개 모델을 비교

- Logistic Regression
- Random Forest

![image](https://github.com/user-attachments/assets/0e753686-49cb-4050-8c2c-6418f6153f14)

Binary defect prediction 문제에서 Logistic regression은 Accuracy 95% - Recall 100%, Random forest는 Accuracy 99% - Recall 90%를 나타냄

Logistic Regression의 회귀계수와 Random Forest의 Feature Importance 분석 결과, 공통적으로 LVDT 변수의 중요도가 가장 높은 것으로 나타남

![image](https://github.com/user-attachments/assets/74d8443f-1522-46cb-9d65-a1e5fdefadb4)

<h2>파일 설명</h2>

- data.ipynb: 데이터 전처리
- motor quality prediction.ipynb: 모델 학습, 추론 및 평가


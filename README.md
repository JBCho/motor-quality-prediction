<h1>Quality Prediction for KorensEM Motor Production</h1>

<h2>개발 내용</h2>
Motor 공정은 여러 개의 중간 공정을 거치며, 각 공정의 중간에 품질 검사를 수행
![image](https://github.com/user-attachments/assets/2685e4a6-8395-4f90-bb74-e6364e2996f0)

이 중 주요 조립 공정에 속하는 OPM90의 공정 데이터를 활용하여 품질 예측 모델을 개발, 2개 모델을 비교

- Logistic Regression
- Random Forest

![image](https://github.com/user-attachments/assets/0e753686-49cb-4050-8c2c-6418f6153f14)

<h2>파일 설명</h2>

- data.ipynb: 데이터 전처리
- motor quality prediction.ipynb: 모델 학습, 추론 및 평가

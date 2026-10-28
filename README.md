# ML Portfolio

머신러닝·딥러닝 수업에서 직접 구현한 Python 프로젝트입니다.
각 노트북 상단의 **Open in Colab** 배지를 누르면 추가 파일 없이 바로 실행할 수 있습니다.

| # | 프로젝트 | 내용 | 결과 | 사용 기술 |
|---|---|---|---|---|
| 1 | [로지스틱 회귀 직접 구현](01_logistic_regression/logistic_regression_from_scratch.ipynb) | 시그모이드·경사하강법·특징 표준화를 NumPy로 직접 구현해 나이·연봉으로 SNS 광고 상품 구매 여부를 예측하고, scikit-learn 모델과 파라미터·정확도·결정경계를 비교 | 테스트 정확도 **86.25%** (scikit-learn 83.75%) | NumPy, pandas, scikit-learn, Matplotlib |
| 2 | [CNN 손글씨 숫자 분류](02_cnn_mnist/cnn_mnist_keras.ipynb) | MNIST로 기본 CNN(Conv 2층 + FC 1층)과 Conv3·FC2를 추가한 개선 CNN을 설계·학습하고 정확도·파라미터 수 비교 | 테스트 정확도 **99.08%** (기본 모델 99.00%) | TensorFlow / Keras |

## 구조

```
ml-portfolio/
├── 01_logistic_regression/
│   ├── logistic_regression_from_scratch.ipynb
│   └── Social_Network_Ads.csv      # 400건, 나이·연봉·구매 여부
└── 02_cnn_mnist/
    └── cnn_mnist_keras.ipynb       # MNIST는 Keras에서 자동 다운로드
```

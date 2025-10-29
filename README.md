# image_reg-class-
## 🧠 Image Regression vs Image Classification

| 구분 | 🖼️ Image Classification | 📈 Image Regression |
|------|--------------------------|---------------------|
| **정의** | 이미지를 **범주(label)** 로 분류하는 문제 | 이미지를 통해 **연속적인 수치값** 을 예측하는 문제 |
| **출력값 형태** | 이산값 (예: 고양이, 개, 사람) | 연속값 (예: 나이 = 25.3, 가격 = 1023.5) |
| **예측 목표** | “무엇인가?” | “얼마인가?” |
| **출력층 활성화 함수** | Softmax 또는 Sigmoid | 없음 (Linear) |
| **대표 손실 함수** | Cross Entropy Loss | MSE, MAE |
| **평가 지표** | Accuracy, F1 Score, Precision | RMSE, MAE, R² Score |
| **대표 모델 구조** | CNN, ResNet, EfficientNet | CNN + Fully Connected Layer |
| **예시** | - 고양이/개 분류<br>- 손글씨 숫자(0~9) 인식<br>- 질병 여부 판별 | - 얼굴로 나이 추정<br>- 위성사진으로 온도 예측<br>- 종양 크기 예측 |
| **출력 예시** | `[1, 0, 0] → 고양이` | `25.7` (나이) |
| **손실 함수 목적** | 분류 정확도 향상 | 수치 예측 오차 최소화 |

---

## 💡 핵심 요약

> 🧩 **Classification** → “무엇인가?”  
> 📊 **Regression** → “얼마인가?”

---

## 🔗 참고 자료

- [Stanford CS231n - Image Classification Notes](http://cs231n.stanford.edu/)
- [TensorFlow - Regression Tutorial](https://www.tensorflow.org/tutorials/keras/regression)
- [PyTorch - Image Classification Tutorial](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html)

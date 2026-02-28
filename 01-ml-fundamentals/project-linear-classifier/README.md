# Mini Project: PyTorch 선형 분류기 from scratch

## 목표
PyTorch를 사용하여 선형 분류기를 처음부터 구현하고 학습시키기.

## 요구사항
1. `nn.Module`을 사용하지 않고 순수 Tensor 연산으로 구현
2. 데이터셋: sklearn의 make_classification 또는 Iris
3. 구현 항목:
   - Forward pass (행렬 곱 + bias)
   - Cross-entropy loss 직접 구현
   - Backward pass (gradient 직접 계산)
   - SGD 업데이트
4. 학습 과정 시각화 (loss curve, decision boundary)
5. `nn.Module` 버전과 결과 비교

## 파일 구조
```
project-linear-classifier/
├── README.md
└── linear_classifier.ipynb
```

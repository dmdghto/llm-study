# Mini Project: 소규모 Language Model 사전학습

## 목표
~10M 파라미터 규모의 언어 모델을 Colab에서 사전학습.

## 요구사항
1. 아키텍처: Phase 4에서 구현한 Mini-GPT 활용
2. 데이터: 한국어/영어 소규모 corpus
3. 학습:
   - Causal Language Modeling (next token prediction)
   - Mixed Precision Training
   - Gradient Accumulation
4. 평가:
   - Perplexity 측정
   - 텍스트 생성 샘플 확인
5. 실험:
   - 모델 크기 변화에 따른 성능
   - 데이터 크기 변화에 따른 성능

## 파일 구조
```
project-small-lm/
├── README.md
└── small_lm.ipynb
```

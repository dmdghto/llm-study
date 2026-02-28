# Mini Project: Mini-GPT

## 목표
소규모 GPT 모델을 scratch에서 구현하고, 텍스트 생성 학습.

## 참고 자료
- [Andrej Karpathy - Let's build GPT from scratch](https://www.youtube.com/watch?v=kCc8FmEb1nY) ⭐

## 요구사항
1. 구현 항목:
   - Token Embedding + Positional Embedding
   - Multi-Head Causal Self-Attention
   - Feed-Forward Network
   - Transformer Block (LayerNorm + Residual)
   - GPT 모델 조립
2. 학습:
   - 소규모 텍스트 데이터 (Shakespeare 등)
   - Cross-entropy loss
   - 텍스트 생성 (temperature, top-k sampling)
3. 실험:
   - 모델 크기에 따른 생성 품질 변화
   - Context length 실험

## 파일 구조
```
project-mini-gpt/
├── README.md
└── mini_gpt.ipynb
```

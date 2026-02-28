# LLM Study 🧠

ML/AI 입문자가 LLM의 이론부터 구현, 활용까지 전 과정을 체계적으로 학습하기 위한 프로젝트.

- **학습 시간**: 주 5-15시간
- **환경**: Google Colab (GPU 무료 제공)
- **프레임워크**: PyTorch
- **최종 목표**: Fine-tuning / RLHF 마스터
- **실무 연계**: ai-ipsonum(AI입소문) 프로젝트와 연계 학습

---

## 진행 상황

### Phase 0: Prerequisites (2-3주)
> 수학 복습 + PyTorch 기초

- [ ] 01-linear-algebra.ipynb - 선형대수 복습
- [ ] 02-probability-stats.ipynb - 확률/통계 복습
- [ ] 03-calculus-for-ml.ipynb - 미적분 복습
- [ ] 04-numpy-pytorch-basics.ipynb - NumPy/PyTorch 기초

### Phase 1: ML Fundamentals (2-3주)
> 머신러닝 핵심 개념과 학습 루프

- [ ] 01-supervised-learning.ipynb - 지도학습 (회귀, 분류)
- [ ] 02-loss-and-optimization.ipynb - 손실함수와 최적화
- [ ] 03-evaluation-metrics.ipynb - 평가 지표
- [ ] project-linear-classifier/ - PyTorch 선형 분류기 from scratch

### Phase 2: Deep Learning (3-4주)
> 신경망 원리와 시퀀스 데이터 처리

- [ ] 01-neural-networks.ipynb - 신경망 기초
- [ ] 02-backpropagation.ipynb - 역전파
- [ ] 03-cnn-basics.ipynb - CNN 기초
- [ ] 04-rnn-and-sequence.ipynb - RNN/LSTM
- [ ] project-text-classifier/ - RNN 텍스트 감정 분류기

### Phase 3: NLP Foundations (3-4주)
> 자연어 처리 파이프라인과 Attention 등장 배경

- [ ] 01-text-preprocessing.ipynb - 텍스트 전처리
- [ ] 02-word-embeddings.ipynb - Word Embeddings
- [ ] 03-text-similarity.ipynb - 텍스트 유사도 🏪
- [ ] 04-seq2seq-attention.ipynb - Seq2Seq + Attention
- [ ] project-korean-ner/ - 한국어 매장명 추출기 🏪

### Phase 4: Transformer Architecture (3-4주) ★
> Transformer를 수식부터 코드까지 완전히 이해

- [ ] 01-attention-mechanism.ipynb - Self-Attention
- [ ] 02-transformer-from-scratch.ipynb - Transformer 구현
- [ ] 03-positional-encoding.ipynb - Positional Encoding
- [ ] 04-bert-vs-gpt.ipynb - BERT vs GPT 비교
- [ ] 05-multi-llm-comparison.ipynb - 멀티 LLM 비교 🏪
- [ ] project-mini-gpt/ - Mini-GPT 구현

### Phase 5: LLM Pre-training (2-3주)
> 대규모 언어 모델 학습 원리

- [ ] 01-tokenization.ipynb - 토크나이저 🏪
- [ ] 02-scaling-laws.ipynb - Scaling Laws
- [ ] 03-training-techniques.ipynb - 학습 기법
- [ ] 04-data-pipeline.ipynb - 데이터 파이프라인
- [ ] project-small-lm/ - 소규모 LM 사전학습

### Phase 6: Fine-tuning & Alignment (4-5주) ★★ 핵심
> LLM을 특정 작업에 맞게 조정

- [ ] 01-transfer-learning.ipynb - Transfer Learning
- [ ] 02-full-finetuning.ipynb - Full Fine-tuning
- [ ] 03-peft-lora.ipynb - PEFT/LoRA
- [ ] 04-rlhf-theory.ipynb - RLHF 이론
- [ ] 05-dpo.ipynb - DPO
- [ ] 06-evaluation.ipynb - 모델 평가
- [ ] project-local-biz-extractor/ - 매장 추출 특화 모델 🏪

### Phase 7: Applications & GEO (3-4주) 🏪
> LLM 활용 기술을 ai-ipsonum에 실전 적용

- [ ] 01-prompt-engineering.ipynb - Prompt Engineering 🏪
- [ ] 02-structured-extraction.ipynb - 구조화 추출 🏪
- [ ] 03-multi-llm-orchestration.ipynb - 멀티 LLM 오케스트레이션 🏪
- [ ] 04-rag-basics.ipynb - RAG
- [ ] 05-evaluation-pipeline.ipynb - 환각 탐지 & 평가 🏪
- [ ] 06-agents-and-tools.ipynb - Agents & Tools
- [ ] project-geo-analyzer/ - ai-ipsonum GEO Analyzer 개선 🏪

---

## 예상 일정

| Phase | 기간 | 누적 | ai-ipsonum 연계 |
|-------|------|------|-----------------|
| 0. Prerequisites | 2-3주 | 2-3주 | - |
| 1. ML Fundamentals | 2-3주 | 4-6주 | - |
| 2. Deep Learning | 3-4주 | 7-10주 | - |
| 3. NLP Foundations | 3-4주 | 10-14주 | 🏪 Fuzzy Match 개선 |
| 4. Transformer ★ | 3-4주 | 13-18주 | 🏪 멀티 LLM 분석 |
| 5. LLM Pre-training | 2-3주 | 15-21주 | 🏪 한국어 토크나이저 |
| 6. Fine-tuning ★★ | 4-5주 | 19-26주 | 🏪 매장 추출 모델 |
| 7. Applications 🏪 | 3-4주 | 22-30주 | 🏪 GEO 파이프라인 개선 |

**총 약 5.5-7.5개월** (주 5-15시간 기준)

---

## 환경 설정

```bash
# 로컬 환경 (선택)
pip install -r requirements.txt

# Google Colab (권장)
# 각 노트북 상단에 필요한 패키지 설치 코드 포함
```

## 핵심 논문

[논문 목록 보기](papers/reading-list.md)

## 참고 자료

[추천 자료 목록](references/resources.md)

# Mini Project: 로컬 비즈니스 매장 추출 특화 모델 🏪

## 목표
오픈소스 LLM을 LoRA로 Fine-tuning하여 한국 로컬 비즈니스 매장명을 정확하게 추출하는 모델 구축.

## ai-ipsonum 연계
- 현재: rule-based 파싱 (`src/lib/parser/`)
- 목표: ML 기반 파싱으로 대체 가능성 검증
- 참고: `ai-ipsonum/src/lib/ai-engines/query-templates.ts`, `src/lib/parser/`

## 요구사항
1. 베이스 모델: Llama 또는 Mistral (오픈소스)
2. 학습 데이터:
   - Input: "강남에서 분위기 좋은 카페 추천해줘" (자연어 쿼리 + AI 응답)
   - Output: `[{"name": "블루보틀", "rank": 1}, ...]` (구조화된 매장 리스트)
   - 소스: ai-ipsonum의 AI 응답 로그 (`batch_queries` 테이블)
3. Fine-tuning: QLoRA (Colab T4 GPU 활용)
4. 평가:
   - 매장명 추출 정확도 (Precision, Recall, F1)
   - rule-based 대비 개선율

## 파일 구조
```
project-local-biz-extractor/
├── README.md
└── local_biz_extractor.ipynb
```

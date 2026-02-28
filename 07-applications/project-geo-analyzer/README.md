# Capstone Project: ai-ipsonum GEO Analyzer 개선 프로토타입 🏪

## 목표
학습한 LLM 기술을 ai-ipsonum에 실전 적용하여 GEO 파이프라인을 개선하는 프로토타입 구축.

## ai-ipsonum 연계
- 참고: `ai-ipsonum/src/lib/ai-engines/`, `src/lib/parser/`, `src/lib/batch/`

## 개선 영역

### 1. 프롬프트 최적화
- 매장 추출 정확도를 높이는 프롬프트 실험
- 현재 대비 개선율 측정

### 2. 구조화 추출
- JSON 모드 / Function Calling으로 파싱 정확도 향상
- rule-based 파싱 대체 가능성 검증

### 3. 환각 필터링
- `unmatched_mentions` 데이터 활용
- hallucination 분류기 구축

### 4. 멀티 엔진 앙상블
- 3개 엔진 결과를 가중 앙상블로 개선
- 단순 합산 대비 정확도 향상

### 5. 결과물
- ai-ipsonum에 PR로 기여할 수 있는 개선안 도출
- 실험 결과 및 분석 리포트

## 파일 구조
```
project-geo-analyzer/
├── README.md
└── geo_analyzer.ipynb
```

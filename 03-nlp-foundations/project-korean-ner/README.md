# Mini Project: 한국어 매장명 추출기 (NER) 🏪

## 목표
한국어 텍스트에서 매장명을 추출하는 NER 모델 구현.
ai-ipsonum의 fuzzy matching 로직을 Python으로 재구현하고 개선.

## ai-ipsonum 연계
- 현재 방식: `fuzzy-match.ts`의 Bigram Dice coefficient
- 참고 파일: `ai-ipsonum/src/lib/parser/fuzzy-match.ts`, `match-response.ts`, `extract-stores.ts`

## 요구사항
1. ai-ipsonum의 Bigram Dice를 Python으로 재구현
2. 유사도 비교 실험:
   - Bigram Dice coefficient
   - Levenshtein distance
   - Embedding 기반 유사도
3. 한국어 특수성 처리:
   - 띄어쓰기 변형 ("블루보틀" vs "블루 보틀")
   - 지점명 제거 ("스타벅스 강남점" → "스타벅스")
   - 정규화 (특수문자, 영문 대소문자)
4. 더 나은 방법 발견 시 ai-ipsonum에 적용 가능한 형태로 정리

## 파일 구조
```
project-korean-ner/
├── README.md
└── korean_ner.ipynb
```

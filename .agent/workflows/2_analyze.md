---
description: 2. 데이터 분석 및 시각화 (Analysis & Viz)
---
// turbo-all

1. **[데이터 확인]** `data/raw/result.csv` 파일이 존재하는지 확인합니다. (없다면 `/1_collect` 실행 안내)
2. **[분석 실행]**
    - CSV 데이터 타입 파악 및 시각화 전략 수립.
    - 파이썬 분석 스크립트 작성 및 실행. (User Rules: `koreanize_matplotlib` 필수)
    - 결과물: `results/figures/`에 그래프 이미지 저장.
3. **[심화 보고서 작성]**
    - 모든 분석 결과와 시각화 이미지는 `results/report.md` 하나의 파일에 정리합니다.
    - **[시각화 필수 요건]** 각 그래프 하단에는 반드시 다음 두 가지를 포함해야 합니다:
        - **해석 가이드**: 그래프가 의미하는 바와 읽는 법을 텍스트로 설명.
        - **데이터 표**: 해당 그래프의 기반이 되는 데이터의 교차표(Cross-tab) 또는 피봇 테이블(Pivot Table)을 마크다운 표로 첨부.
    - `walkthrough.md`에는 `report.md`의 요약본과 링크만 남깁니다.

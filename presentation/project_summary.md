# 발표 초안

## 1. 문제 정의

동일한 기대수익률에서도 변동성 또는 기간이 바뀌면 경로 리스크는 얼마나 커지는가?

## 2. 데이터와 가정

- 합성 샘플 데이터: `data/sample/gbm_path_assumptions.csv`
- 원본 강의자료/코드 직접 사용 없음
- 재현 가능한 baseline 실행을 우선 구성

## 3. 방법

GBM 경로를 생성하고 terminal 분포, drawdown, barrier touch 확률을 요약한다.

## 4. 현재 산출물

- 실행 스크립트: `python -m src.run_baseline`
- 결과 표: `outputs/tables/baseline_results.csv`

## 5. 후속 작업

- 실제 데이터 연결
- 민감도 분석
- 차트/보고서 산출
- 프로젝트별 상세 검증

# Sample Data

이 폴더의 `gbm_path_assumptions.csv`는 baseline 계산을 검증하기 위해 만든 합성 데이터입니다.

## Columns

- `scenario_id`
- `spot`
- `annual_mu`
- `annual_sigma`
- `horizon_days`
- `n_steps`
- `n_paths`
- `down_barrier`
- `seed`

## Usage

```bash
python -m src.run_baseline
```


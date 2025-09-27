# Enpal dbt Assessment

## What’s inside
- Staging models (`models/staging`)
- Intermediate models (`models/intermediate`)
- Reporting model (`models/reporting/rep_sales_funnel_monthly.sql`)
- Seeds (`seeds/`): `map_stage_to_funnel.csv`, `map_activity_to_funnel.csv`, etc.
- Linting config: `.sqlfluff`

## Prereqs
- Python 3.11+
- dbt-core + dbt-postgres
- (Optional) sqlfluff

## Setup
```bash
python -m venv .venv
. .venv/Scripts/Activate.ps1  # Windows PowerShell
pip install -r requirements.txt  # or: pip install dbt-postgres sqlfluff



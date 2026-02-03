# dbt Workflow for this report:

staging: retail.csv raw data,  extra_data.parquet

  ↓

intermediate: join

  ↓

marts: retail_clean.csv

  ↓

python analysis


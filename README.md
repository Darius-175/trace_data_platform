## Project Structure

```text
trace-analytics/
│
├── dbt/
│   ├── dbt_project.yml
│   ├── packages.yml
│   ├── models/
│   │   ├── sources/
│   │   │   └── posthog_sources.yml
│   │   ├── staging/
│   │   │   ├── stg_posthog_events.sql
│   │   │   └── staging.yml
│   │   ├── core/
│   │   │   ├── fct_events.sql
│   │   │   ├── dim_users.sql
│   │   │   ├── fct_user_daily_activity.sql
│   │   │   └── core.yml
│   │   └── marts/
│   │       ├── mart_daily_product_metrics.sql
│   │       └── marts.yml
│   └── macros/
│
├── airflow/
│   └── dags/
│       └── posthog_dbt_hourly.py
│
├── config/
│   └── profiles.yml
│
├── .github/
│   └── workflows/
│       └── dbt_ci.yml
│
├── requirements-dbt.txt
├── .gitignore
└── README.md
```


## Project Structure

```text
trace-data-platform/
├── dbt/
│   ├── dbt_project.yml
│   ├── packages.yml
│   ├── models/
│   │   ├── staging/
│   │   │   ├── posthog/
│   │   │   ├── supabase/
│   │   │   └── backend/
│   │   ├── intermediate/
│   │   ├── core/
│   │   └── marts/
│   │       ├── product/
│   │       ├── growth/
│   │       └── revenue/
│   ├── snapshots/
│   ├── tests/
│   ├── macros/
│   └── seeds/
├── airflow/
│   ├── dags/
│   └── tests/
├── docker/
│   └── dbt/
│       └── Dockerfile
├── deploy/
│   └── dbt/
│       └── profiles.yml
├── scripts/
├── docs/
│   └── architecture.md
├── .github/
│   └── workflows/
│       ├── dbt-ci.yml
│       └── deploy.yml
├── requirements-dbt.txt
├── .gitignore
└── README.md
```


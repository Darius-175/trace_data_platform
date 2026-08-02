# trace_data_pipline

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
├── requirements-dbt.txt
├── .gitignore
├── .github/
│   └── workflows/
│       ├── dbt-ci.yml
│       └── deploy.yml
└── README.md

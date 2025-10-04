markdown# Data Engineering Portfolio

**ETL pipelines, data quality frameworks, and production database design from EPA research background.**

## About This Project

This repository contains data engineering work developed during my EPA postdoc and subsequent learning. Focuses on ETL patterns, data validation, API integration, and database design.

**Core Capabilities:**
- Production ETL pipelines with Python
- Database schema design and management (PostgreSQL, Supabase)
- API integration and data ingestion
- Data quality validation and monitoring
- Modular, scalable code architecture

## Technical Stack

- **Python:** SQLAlchemy, Pandas, Polars, Pydantic, logging frameworks
- **Databases:** PostgreSQL, Supabase (with RLS), SQLite
- **APIs:** RESTful integration, authentication, error handling
- **Data Formats:** CSV, Parquet, JSON, database dumps
- **Tools:** Git, environment management, structured logging

## Key Components

### ETL Pipelines
- API data extraction with error handling
- Data transformation and cleaning
- Parameterized database loading (SQL injection prevention)
- Incremental update patterns

### Data Quality
- Schema validation with Pydantic
- Data profiling and anomaly detection
- Reconciliation checks
- Structured logging with JSON output

### Database Engineering
- Schema design for relational data
- Foreign key constraints and referential integrity
- Row-level security implementation
- Database dumps and restoration procedures

## Project Structure
├── pipelines/          # ETL pipeline implementations
├── validation/         # Data quality and schema validation
├── database/          # Schema definitions and migrations
├── scripts/           # Utility scripts and automation
└── logs/              # Structured logging output

## Background

Built during EPA postdoc doing epidemiology and data science. Transitioned from research data work to production data engineering patterns. Now focusing on analytics engineering (see separate repo).

**Related Skills:** R (dplyr, data.table), statistical modeling, handling messy real-world datasets, research methodology.

## Contact

[LinkedIn] | [Email]

---

*This repository demonstrates data engineering fundamentals. Current focus is analytics engineering - see [analytics-engineering repo] for dimensional modeling and dbt work.*

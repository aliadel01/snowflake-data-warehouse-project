# end-to-end-etl-pipeline
A modern end-to-end ETL pipeline that extracts data with Python, loads it into Snowflake, transforms it using dbt, and orchestrates the entire workflow with Kestra.
```
end_to_end_etl/
│── venv/
│── src/
│   ├── extract/
│   ├── load/
│   ├── transform/
│   └── utils/
│── dbt/
│── kestra/
│── requirements.txt
│── .env
│── README.md
```
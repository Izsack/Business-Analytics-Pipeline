# Business Analytics Data Platform

## AWS Glue • PySpark • Amazon S3 • Athena • QuickSight • IAM

An end-to-end cloud analytics architecture designed to transform
manually generated business reports into a reusable, governed,
and scalable business intelligence platform.

---

## Architecture

SQL Database
     │
     ▼
AWS Glue / PySpark
     │
     ▼
Amazon S3
 ┌───────────┐
 │ Raw       │
 │ Processed │
 │ Curated   │
 └───────────┘
       │
       ▼
Glue Data Catalog
       │
       ▼
Amazon Athena
       │
       ▼
Amazon QuickSight
       │
       ▼
Business Users

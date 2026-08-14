# Business Analytics Data Platform

## AWS Glue • PySpark • Amazon S3 • Athena • QuickSight • IAM

An end-to-end cloud analytics architecture designed to transform
raw business data into a reusable, governed,
and scalable business intelligence dashboards.

AWS analytics pipeline: SQL database on EC2, transformed by Glue and PySpark into an S3 data lake, queried with Athena and visualised in QuickSight.

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

# SQL-data-warehouse-project
Building a modern data warehouse using SQL Server, including ETL processes, data modelling, and analytics
📌 About This Project

Welcome to my Data Warehouse & Analytics Project! This repository showcases a complete, real-world data warehousing solution — built from the ground up using SQL Server and modern data engineering best practices.

It covers everything from ingesting raw data to delivering business-ready insights: designing a scalable architecture, building ETL pipelines, modeling data into a clean star schema, and writing SQL-based reports that answer real business questions.

This project was built as a portfolio piece to demonstrate hands-on skills in data engineering and analytics — the kind of work a Data Engineer, Data Analyst, or BI Developer would do on the job.

🏗️ Data Architecture

This project follows the Medallion Architecture — a layered approach (🥉 Bronze → 🥈 Silver → 🥇 Gold) that keeps data clean, traceable, and analytics-ready at every stage.

Layer	Purpose
🥉 Bronze	Raw, unprocessed data ingested as-is from source systems (CSV files) into SQL Server
🥈 Silver	Cleansed, standardized, and normalized data — ready for transformation
🥇 Gold	Business-ready data modeled into a star schema for reporting and analytics

📖 Project Overview

This project involves:

🏛️ Data Architecture — Designing a modern data warehouse using Bronze, Silver, and Gold layers
🔄 ETL Pipelines — Extracting, transforming, and loading data from source systems into the warehouse
🧱 Data Modeling — Building fact and dimension tables optimized for fast, reliable analytical queries
📊 Analytics & Reporting — Writing SQL-based reports and dashboards that turn raw data into actionable insights

🛠️ Tools & Resources

Everything used in this project is completely free:

Tool	Purpose
📂 Datasets	Source data provided as CSV files
🖥️ SQL Server Express	Lightweight server for hosting the database
🧰 SQL Server Management Studio (SSMS)	GUI for managing and querying the database
🌱 Git & GitHub	Version control and project collaboration

🚀 Project Requirements
🔧 Part 1 — Building the Data Warehouse (Data Engineering)

Objective: Develop a modern data warehouse in SQL Server to consolidate sales data and enable analytical reporting.

Specifications:

Data Sources — Import data from two source systems (ERP and CRM) provided as CSV files
Data Quality — Cleanse and resolve data quality issues before analysis
Integration — Merge both sources into a single, user-friendly data model built for analytical queries
Scope — Focus on the latest dataset only (no historization required)
Documentation — Clearly document the data model to support both business stakeholders and analytics teams
📊 Part 2 — BI Analytics & Reporting (Data Analysis)

Objective: Develop SQL-based analytics to deliver clear insights into:

👥 Customer Behavior
📦 Product Performance
📈 Sales Trends

These insights give stakeholders the key metrics they need to make confident, data-driven decisions.

👤 About Me

Thanks for checking out my project! I'm building my portfolio in SQL development, data engineering, and analytics — feel free to explore the code, open an issue, or connect with me

📜 License

This project is licensed under the MIT License — feel free to use, learn from, and build on it.

#PROJECT OVERVIEW
This project implements an ETL (Extract, Transform, Load) pipeline to process and analyze the NYC Yellow Taxi Trip Data (2017), simulating a retail data lake for generating actionable insights. The pipeline extracts trip data from a CSV file, transforms it to compute key metrics (e.g., average trip distance and fare by pickup location), and loads the results into a PostgreSQL database for efficient querying. This project demonstrates core data engineering skills, including data processing, database management, and performance optimization, with potential for migration to AWS services like S3, Glue, and Redshift.

#OBJECTIVES
Extract and clean large-scale taxi trip data for analysis.
Aggregate data to provide insights into trip patterns by pickup location.
Store results in a relational database for fast querying and validation.
Lay the foundation for a cloud-based data lake using AWS technologies.

#KEY FEATURES
Extract: Reads NYC Taxi data from a CSV file using Pandas, selecting only relevant columns to optimize memory usage.
Transform: Cleans data (removes invalid records, handles missing values) and aggregates metrics (average trip distance, fare, and trip count) by pickup location.
Load: Uses SQLAlchemy to efficiently load aggregated data into a PostgreSQL table with an optimized index.
Validation: Executes SQL queries to verify data integrity and retrieve top pickup locations by trip count.
Performance: Tracks execution time for each ETL stage and optimizes database queries with indexing.

#TECHNOLOGIES USED
Programming Language: Python 3.8+
Libraries: Pandas, psycopg2, SQLAlchemy
Database: PostgreSQL
Data Source: NYC Yellow Taxi Trip Data (public dataset)

#FUTURE SCOPE: AWS (S3, Glue, Redshift, QuickSight)

#PREREQUISITES
Python 3.8+ and Jupyter Notebook (optional for .ipynb execution)
PostgreSQL installed and running locally
Python packages: pandas, psycopg2-binary, sqlalchemy
NYC Taxi dataset (downloaded from NYC TLC Trip Record Data)

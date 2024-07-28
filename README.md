# AppleDataAnalysis
Flow Diagram
![Flowcharts](https://github.com/user-attachments/assets/bacfc9f3-86a7-4404-8a2e-a6011ab3fc79)


Data Processing Workflow
Step 1: Reading Data
We start by reading data from multiple sources:

CSV files
Parquet files
Delta Tables
Step 2: Factory Pattern
Using the factory pattern, we have implemented factory methods to efficiently extract and load data from these diverse sources.

Step 3: Transforming Data
The data is then transformed using PySpark, enabling powerful and scalable data processing.

Step 4: Storing Data
Finally, the transformed data is stored in:

Delta Tables for efficient updates and time travel queries.
Data Lake for long-term storage and further analysis.

Steps to run:
Step 1: clone this repository
Step 2: Import AppleAnalysis.zip zip file into databricks
Step 3: Add Data files in databriks DBFS
Step 4: Run apple_analysis notbook

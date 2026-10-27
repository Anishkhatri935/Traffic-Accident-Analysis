# Traffic Accident Big Data Analytics Using Databricks

## Project Overview

This project was developed for BBIM Big Data Analytics Assessment 2 at New Zealand Skills and Education (NZSE).

The project demonstrates the implementation of a big data framework using Databricks, Apache Spark and Delta Lake to analyse 1,000,000 traffic accident records.

## Project Objectives

1. Implement an ETL pipeline using Apache Spark and Delta Lake.
2. Apply MapReduce-style processing to analyse monthly traffic accident patterns.
3. Develop machine-learning models for accident-severity classification.
4. Predict monthly accident counts using time-series techniques.
5. Evaluate model performance, optimisation and limitations.

## Technologies Used

- Databricks Serverless
- Apache Spark and PySpark
- Delta Lake
- Spark MLlib
- Python
- Matplotlib

## Dataset

A publicly available traffic accident dataset obtained from Kaggle, containing 1,000,000 accident records.

The dataset includes accident severity, date, location, weather, road conditions and traffic-related attributes.

## Implementation

### Task 1 — Big Data Framework

Data ingestion, validation, transformation, Delta Lake storage and optimisation using Databricks.

### Task 2 — MapReduce

Monthly and severity-based accident aggregation using Spark DataFrame transformations, with partitioning and performance comparisons.

### Task 3 — Machine Learning

Random Forest classification for accident severity and seasonal naïve and Random Forest regression models for monthly accident prediction.

### Task 4 — Discussion and Conclusion

Critical interpretation of the results, limitations, optimisation outcomes and future research opportunities.

## Key Results

- Processed 1,000,000 traffic accident records.
- Generated 196 month–severity aggregation groups.
- Achieved 52.17% classification accuracy with the tuned Random Forest.
- Improved Critical-class recall from 1.33% to 16.54%.
- Achieved a forecasting MAE of 182.67 using the seasonal naïve baseline.

## How to Reproduce

1. Create or access a Databricks workspace with an appropriate Spark environment.
2. Download the project notebook from this repository.
3. Import the notebook into Databricks.
4. Obtain the original dataset from the public source.
5. Update dataset paths and the Delta table location for your workspace.
6. Run the notebook cells in sequence.
7. Review the resulting tables, charts and evaluation metrics.

The notebook was developed using Databricks Serverless. Execution time and resource availability may differ across environments.

## Limitations

The classification model has limited Critical-class recall. The forecasting dataset contains only a short monthly history, and the reported regression results represent rolling one-step-ahead evaluation.

## Author

Anish khatri — BBIM, NZSE, Auckland, New Zealand.

# Cloud Data Processing Project

This repository contains the implementation and documentation of a cloud-based data processing project developed using Apache Spark on the Databricks platform. The project focuses on analyzing large-scale datasets, applying machine learning techniques, and evaluating scalability using different levels of parallelism.

# Project Structure

The repository is organized as follows:
cloud-project-pyspark/
├── code/        # Databricks notebook
├── report/      # Final project report
├── visuals/     # Architecture diagrams and result charts
├── data/        # Small sample datasets
├── README.md    # Project description and usage guide
└── .gitignore   # Git ignore rules


# Code

The `code/` folder contains the Databricks notebook used to run the full pipeline.  
The notebook includes:
- Data loading from Databricks Volumes
- Data validation and preprocessing
- Descriptive statistics
- Machine learning jobs (regression, classification, clustering, outlier detection)
- Performance benchmarking using different parallelism levels


# Report

The `report/` folder contains the final project report in PDF format.  
The report explains:
- System requirements
- Architecture and design
- Implementation details
- Experiments and evaluation
- User support and conclusion


# Visuals

The `visuals/` folder contains figures used in the report, such as:
- Architecture diagrams
- Pipeline flow diagrams
- Benchmark and scalability charts

These visuals are referenced in the report sections.


# Data

The `data/` folder contains only small sample datasets or example files.  
Large datasets used in the experiments (such as HIGGS or NYC Taxi data) are not included in this repository and were stored in Databricks Volumes during execution.


# How to Run the Project

1. Open the Databricks notebook from the `code/` folder inside a Databricks workspace.
2. Upload or place your dataset in Databricks Volumes.
3. Set the required widget parameters (dataset path, file type, options).
4. Run the notebook to execute the pipeline and view results.


# Video Demonstration

A short video demonstration (5–7 minutes) is provided to show how the program works, including:
- Running the notebook
- Setting parameters
- Executing ML jobs
- Viewing benchmark results

(Video link is provided in the project report.)


# Notes

- The project was executed on Databricks using PySpark in Serverless mode.
- Performance results depend on dataset size and selected options.
- Each execution run generates separate output folders to ensure reproducibility.

# ETL Pipeline using PySpark

## Overview

This project demonstrates an **ETL pipeline** using **PySpark**, designed to read, transform, and load data into destinations like **DBFS** and **Delta Tables**. It uses a modular approach with factory design patterns for extensibility.

## Features

- Supports multiple data sinks: DBFS, partitioned DBFS, Delta Tables.
- Modular codebase with reusable components for reading, transforming, and loading data.
- Optimized for large-scale data processing.

## Technologies Used

- **Apache Spark**
- **Databricks**
- **Python**

## Installation

1. Clone the repository:
   git clone https://github.com/Amolbhalerao8/Project-608.git

2. Set up your Spark/Databricks environment.

3. Upload code to Databricks or Jupyter notebook.

4. Run the main.py script locally or as a Databricks notebook.
   [ 1.reader_facatory
     2. loader_factory
     3. extractor
     4. transform
     5. loader
   ]
        



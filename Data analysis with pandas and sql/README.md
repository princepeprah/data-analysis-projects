# Electronics Sales Data Analysis With Pandas and SQL

## Overview

This repository contains code for loading, analyzing, and visualizing data from an `electronics` table in a PostgreSQL database. The dataset includes information on sales, customer ratings, categories, brands, and timestamps. The code is written in Python and leverages libraries like `pandas`,  and `SQLAlchemy` for data manipulation, visualization, and database connectivity.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Environment Variables](#environment-variables)
  - [Setting Up `.env` File](#setting-up-env-file)
  - [Environment Variables Breakdown](#environment-variables-breakdown)
- [Database Connection](#database-connection)
  - [Connection Function](#connection-function)
  - [Testing Connection](#testing-connection)
- [Data Loading](#data-loading)
  - [Loading Data from CSV](#loading-data-from-csv)
  - [Loading Data from SQL Query](#loading-data-from-sql-query)
  - [Loading Data from SQL Table](#loading-data-from-sql-table)
- [Data Insertion](#data-insertion)
  - [Inserting Data into PostgreSQL](#inserting-data-into-postgresql)
  - [Handling Duplicates](#handling-duplicates)
  - [Validating Insertion](#validating-insertion)
- [Data Analysis](#data-analysis)
  - [Customer Ratings Distribution](#customer-ratings-distribution)
  - [Duplicate Records Analysis](#duplicate-records-analysis)
  - [Null Values Check](#null-values-check)
  - [Yearly Sales Analysis](#yearly-sales-analysis)
  - [Sales by Category](#sales-by-category)
  - [Top Selling Items](#top-selling-items)
  - [Sales by Brand](#sales-by-brand)
- [Visualizations](#visualizations)
  - [Setting Up Visualization Libraries](#setting-up-visualization-libraries)
  - [Creating Plots](#creating-plots)
  - [Customizing Visuals](#customizing-visuals)
  - [Saving and Exporting Plots](#saving-and-exporting-plots)
- [Error Handling](#error-handling)
  - [Database Connection Errors](#database-connection-errors)
  - [Data Loading Errors](#data-loading-errors)
  - [Data Insertion Errors](#data-insertion-errors)
  - [Logging and Debugging](#logging-and-debugging)


## Setup
Environment Variables
The following environment variables need to be set in a .env file in the project root for the code to run correctly:

DATA_PATH: Path to the CSV file containing the data.
DB_USER: PostgreSQL username.
DB_PWD: PostgreSQL password.
DB_HOST: PostgreSQL host.
DB_PORT: PostgreSQL port.
DB_NAME: PostgreSQL database name.

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or higher
- PostgreSQL database
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/princepeprah/data-analysis-projects.git
   cd Data analysis with pandas and sql

## Conclusion

This analysis provided insightful findings regarding the sales data within the electronics industry. By utilizing various SQL queries and Python-based data processing techniques, we were able to:

- Identify key trends in customer ratings, revealing the overall customer satisfaction levels.
- Detect and handle duplicate records, ensuring the integrity of the dataset.
- Analyze null values to maintain data quality, leading to more accurate analysis results.
- Explore yearly sales trends, uncovering peaks and declines in sales over time.
- Examine sales distribution by category and brand, highlighting the most popular categories and brands


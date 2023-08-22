# Automated Weather Data ETL using Apache Airflow

## Project Overview

This project demonstrates the development and implementation of an automated ETL (Extract, Transform, Load) process for fetching current weather data from the OpenWeatherMap API, transforming the data, and loading it into an S3 bucket. The ETL process is orchestrated using Apache Airflow on an Amazon EC2 instance.

## Table of Contents

1. [Project Objective](#project-objective)
2. [Technologies Used](#technologies-used)
3. [Project Architecture](#project-architecture)
4. [Key Steps](#key-steps)
5. [Impact](#impact)
6. [Usage](#usage)
7. [Screenshots](#screenshots)

## Project Objective

The primary objective of this project is to build an end-to-end ETL pipeline that automates the process of fetching real-time weather data, transforming it, and storing it for analysis. The utilization of Apache Airflow ensures that the ETL process is scheduled and executed reliably.

## Technologies Used

- Amazon EC2
- Apache Airflow
- OpenWeatherMap API
- Python
- Pandas
- Amazon S3

## Project Architecture

The project architecture comprises the following components:

- **Amazon EC2 Instance:** Hosts the ETL process and Apache Airflow.
- **Apache Airflow:** Orchestrates and schedules the ETL tasks.
- **OpenWeatherMap API:** Source of real-time weather data.
- **Python Scripts:** Responsible for data extraction, transformation, and loading.
- **S3 Bucket:** Stores the transformed weather data.

## Key Steps

1. **Data Extraction**: The ETL process begins by making an API request to the OpenWeatherMap API to retrieve real-time weather data for a specific location.

2. **Data Transformation**: The extracted data is transformed using Python and Pandas. Temperature values are converted from Kelvin to Fahrenheit, and additional information is extracted to create a comprehensive dataset.

3. **Data Loading**: The transformed data is loaded into an S3 bucket, making it easily accessible for further analysis.

## Impact

This project streamlines the process of collecting and storing weather data, reducing manual effort and ensuring data accuracy. It enables data analysts and scientists to access clean, formatted weather data for various analytical purposes.

## Usage

- **Data Analysis**: The stored weather data can be used for trend analysis, seasonal comparisons, and correlation studies with other datasets.
- **Predictive Modeling**: Machine learning models can be trained using historical weather data to predict future weather conditions.
- **Decision Making**: Businesses can leverage the weather data to make informed decisions related to operations, marketing, and resource allocation.

## Screenshots

### Amazon EC2 Instance
![image](https://github.com/george-moses/Weather-Data-ETL/assets/107324220/16d0814c-d9b7-4f1d-9a6f-9850c6cd48db)

### Airflow DAG
![image](https://github.com/george-moses/Weather-Data-ETL/assets/107324220/7c759f55-23f6-47e5-8bba-4b41d8a8863d)

### Amazon S3 Bucket with Transformed Data
![image](https://github.com/george-moses/Weather-Data-ETL/assets/107324220/e43a27b3-baae-472b-84b8-bc886b47c60d)

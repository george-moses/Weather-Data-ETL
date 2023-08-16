# Automated Weather Data ETL using Apache Airflow

## Project Overview

This project demonstrates the development and implementation of an automated ETL (Extract, Transform, Load) process for fetching current weather data from the OpenWeatherMap API, transforming the data, and loading it into an S3 bucket. The ETL process is orchestrated using Apache Airflow on an Amazon EC2 instance.

## Table of Contents

1. [Project Objective](#project-objective)
2. [Technologies Used](#technologies-used)
3. [Project Architecture](#project-architecture)

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

- Amazon EC2 Instance: Hosts the ETL process and Apache Airflow.
- Apache Airflow: Orchestrates and schedules the ETL tasks.
- OpenWeatherMap API: Source of real-time weather data.
- Python Scripts: Responsible for data extraction, transformation, and loading.
- S3 Bucket: Stores the transformed weather data.




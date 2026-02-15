# Stock Market Kafka Real Time Data Engineering Project

## Introduction 
An end-to-end Real-Time Data Engineering Project built using Apache Kafka, Python, and AWS to simulate and process stock market streaming data.
This project demonstrates real-time ingestion, cloud storage, schema discovery, and serverless analytics using modern data engineering tools.
Used Python, Apache Kafka, and AWS (S3, EC2, Glue, Athena) to build a real-time stock market data pipeline and perform SQL-based analytics.

## Architecture 
<img src="Architecture.jpg">

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
-Streaming Platform
1. Apache Kafka


## Dataset Used
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline) 

Here is the dataset used in the project - https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv

Implementation Steps
1️⃣ Infrastructure Setup

Launched EC2 instance

Installed and configured Apache Kafka

Created Kafka topic for stock data

2️⃣ Real-Time Data Streaming

Developed Python Kafka Producer

Streamed CSV data line-by-line in real-time

Implemented controlled data ingestion speed

3️⃣ Data Consumption & Storage

Built Kafka Consumer in Python

Converted records into structured JSON

Stored streaming data into Amazon S3

4️⃣ Metadata & Query Layer

Configured AWS Glue Crawler

Automatically detected schema

Created tables in Glue Data Catalog

Queried data using Athena (SQL)

📊 Sample Analytical Queries (Athena)

Top performing stocks by daily change

Average closing price by index

Volume trend analysis

Aggregation & filtering using SQL

🧠 Concepts Demonstrated

Real-Time Streaming Architecture

Event-Driven Data Processing

Distributed Messaging Systems

Cloud Data Lake Architecture

Schema Discovery & Metadata Management

Serverless Querying

End-to-End ETL Pipeline

📌 Key Highlights

✔ Built scalable real-time data pipeline
✔ Implemented Kafka Producer & Consumer
✔ Designed AWS-based Data Lake
✔ Automated schema detection using Glue
✔ Performed analytics using Athena
✔ Demonstrated cloud-native data engineering practices

🎯 Business Use Case

This architecture can be extended for:

Real-time financial market analytics

Fraud detection systems

Banking transaction monitoring

Live dashboard data pipelines

Event-driven enterprise systems



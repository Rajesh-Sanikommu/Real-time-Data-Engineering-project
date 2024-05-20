# Real-time Stock Market Data Processing Using Kafka and AWS 

## Introduction

This project demonstrates the design and implementation of a real-time data processing system using Apache Kafka integrated with various AWS services. It simulates stock market activities, captures these events, and processes the data through a Kafka pipeline that includes data ingestion, processing, storage, and analysis. The ultimate goal is to enable real-time analytics on stock market data.

## Steps Followed to Complete the Project

### Data Simulation
- **Tools used:** Python 
- **Description:** Simulated stock market data is generated using Python scripts to mimic real-time data production.

### Data Production and Ingestion into Kafka
- **Tools used:** Apache Kafka, EC2
- **Description:** The simulated data is sent to Kafka running on an Amazon EC2 instance, where Kafka acts as the central hub for data streams.

### Data Storage
- **Tools used:** Amazon S3
- **Description:** Consumed data from Kafka is stored in Amazon S3, providing durable and scalable storage.

### Data Cataloging
- **Tools used:** AWS Glue Catalog, crawlers
- **Description:** Used AWS Glue crawlers to scan data in S3 and generate metadata tables in the AWS Glue Data Catalog, facilitating structured data analysis.

### Data Querying and Analysis
- **Tools used:** Amazon Athena
- **Description:** Queried data stored in S3 is and analyzed using SQL in Amazon Athena, offering insights without the need to load data into traditional databases.

## Project Architecture
This project utilizes the following components:  
**Python script to simulate real-time data** ==> **Apache Kafka on EC2** ==>  **Amazon S3** ==> **AWS Glue Crawler** ==> **Amazon Athena**

## Technology used
* Python
* Apache Kafka
* Amazon Web Service (AWS)
   S3 (Simple Storage Service)  
   Athena  
   Glue Crawler  
   Glue Catalog    
   EC2




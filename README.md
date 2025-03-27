📈 Stock Market Real-Time Data Pipeline with Kafka & AWS
This project demonstrates a real-time data streaming pipeline that simulates stock market data, streams it via Apache Kafka, and stores it in Amazon S3 for analytics using AWS Glue and Amazon Athena.

🔧 Tech Stack:
Apache Kafka (on Amazon EC2)

Python for producer & consumer

Amazon S3 for storage

AWS Glue (Crawler & Data Catalog)

Amazon Athena for querying

s3fs, boto3, kafka-python

🔄 Workflow:
Producer: Simulates stock market data using Python and sends records to a Kafka topic.

Kafka Broker: Hosted on EC2, handles the real-time stream.

Consumer: Reads messages from Kafka and writes them as .json files to an S3 bucket.

Glue Crawler: Automatically catalogs the incoming data in S3.

Athena: Used to query and analyze the data using SQL.

📌 Use Case:
Ideal for stock analytics, real-time dashboards, event-driven architecture demos, or as a learning tool for Kafka + AWS integrations.


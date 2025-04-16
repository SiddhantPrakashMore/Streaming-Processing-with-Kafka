## 📈 Stock Market Real-Time Data Pipeline with Kafka & AWS

This project demonstrates a real-time data streaming pipeline that simulates stock market data using a Python-based producer, streams it via Apache Kafka (hosted on EC2), and stores the data in Amazon S3. The pipeline is integrated with AWS Glue and Athena for metadata cataloging and serverless querying.

![image](https://github.com/user-attachments/assets/04d744b4-266b-40fd-a3d7-f845b7663118)

---

## 🔧 Tech Stack

- **Apache Kafka** (on Amazon EC2)
- **Python** for producer & consumer
- **Amazon S3** for storage
- **AWS Glue** (Crawler & Data Catalog)
- **Amazon Athena** for querying
- **Libraries:** `s3fs`, `boto3`, `kafka-python`

---

## 🔄 Workflow

- **Producer:** Simulates stock market data using Python and sends records to a Kafka topic.
- **Kafka Broker:** Hosted on EC2, manages the real-time stream.
- **Consumer:** Reads messages from Kafka and writes them as `.json` files to Amazon S3.
- **Glue Crawler:** Automatically catalogs the incoming data in S3.
- **Athena:** Used to query and analyze the data using SQL.

---

## 📌 Use Case

Ideal for stock analytics, real-time dashboards, event-driven architecture demos, or as a learning tool for Kafka + AWS integrations.

# Stock Real-time Analysis

## Overview
This project provides a comprehensive analysis of stock market indices from various global markets. 
Using historical data, it visualizes trends, fluctuations, and market dynamics over decades. 
By leveraging real-time streaming with Kafka, AWS Glue, Athena, and Power BI, the project delivers actionable insights into global market performance.

## Technologies Used
- **Kafka:** Streams data into the topic for consumer applications & Fetches data from Kafka topics and stores it into AWS S3
- **AWS S3:** Stores preprocessed stock market data for analysis and visualization.
- **AWS Glue:** Creates a data catalog for the stock indices dataset & Automates ETL processes for structured data preparation
- **AWS Athena:** Executes SQL queries on the data stored in S3 & Provides fast and interactive data exploration without managing servers
- **Power BI:** Creates interactive data visualizations highlighting gains, losses, and time series data.

## Visualizations
This visualization captures the significant fluctuations in stock indices value over time. 
It highlights both sharp gains and steep losses, enabling quick identification of impactful events, such as the global financial crisis. 

## Time Series Chart
![Time Series](images/time%20series.png)

## Gains and Losses
![Gains and Losses](images/gains%20and%20losses.png)
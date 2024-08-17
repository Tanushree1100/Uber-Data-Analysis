# Uber-Data-Analysis

## Overview

This project aims to leverage the power of data analytics to gain insights from Uber trip data, utilizing a combination of Google Cloud Platform (GCP) services, Python programming, and modern data pipeline tools. The project involves end-to-end data processing, from raw data ingestion to insightful visualization.

The main goal is to analyze taxi trip records from New York City's TLC (Taxi & Limousine Commission) data, which includes information such as pick-up and drop-off locations, trip distances, fares, and passenger counts. By processing and analyzing this data, the project aims to uncover patterns, trends, and anomalies in urban transportation.

### Key Objectives:
1. **Data Ingestion and Storage**: Raw data is ingested from the source and stored securely in Google Cloud Storage.
2. **Data Processing and Transformation**: Python scripts running on GCP Compute Instances are used to clean, process, and transform the data into a format suitable for analysis.
3. **Data Pipelines**: Automated data pipelines are built using Mage to streamline the data flow from ingestion to analysis.
4. **Data Analysis**: BigQuery is employed to perform complex queries and analyze large datasets efficiently.
5. **Data Visualization**: Looker Studio is used to create interactive dashboards and reports that provide actionable insights from the data.

This project is designed to be scalable and can be adapted for different datasets or extended with additional features, such as machine learning models or real-time data processing. It also serves as a practical example of how to build a modern data analytics solution using cloud-based technologies and open-source tools.

## Project Architecture

The architecture of the project includes the following components:

1. **Data Storage**: Data is stored in Google Cloud Storage.
2. **Compute Instance**: Python scripts are executed on a GCP Compute Instance.
3. **Data Pipeline**: The Mage data pipeline tool is used to automate data ingestion and transformation.
4. **BigQuery**: Data is loaded into BigQuery for analysis.
5. **Visualization**: Looker Studio is used to create interactive reports and dashboards.

## Technology Stack

- **Programming Language**: Python
- **Google Cloud Platform Services**:
  - **Google Cloud Storage**: For storing raw and processed data.
  - **Compute Engine**: For running data processing scripts.
  - **BigQuery**: For performing large-scale data analysis.
  - **Looker Studio**: For creating visual dashboards.
- **Data Pipeline Tool**: [Mage](https://www.mage.ai/)
  - Contribute to this open-source project here: [Mage GitHub Repository](https://github.com/mage-ai/mage-ai)

## Dataset

The dataset used in this project consists of TLC Trip Record Data, which includes detailed records of yellow and green taxi trips in New York City. The data captures:

- Pick-up and drop-off dates/times
- Pick-up and drop-off locations
- Trip distances
- Itemized fares
- Rate types
- Payment types
- Driver-reported passenger counts

### Dataset Source
- [Uber Data CSV](https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv)

### Additional Resources
- [TLC Trip Record Data Website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- [Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

## Installation and Setup

### Prerequisites

- Google Cloud Platform Account
- Python 3.x installed locally
- GCP SDK installed locally

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/uber-data-analytics
   cd uber-data-analytics
   ```

2. **Set up a GCP Project**
   - Create a project in GCP and enable the necessary APIs: BigQuery, Compute Engine, and Cloud Storage.

3. **Upload Data to Google Cloud Storage**
   - Upload the dataset to a GCP Storage Bucket.

4. **Set up a Compute Instance**
   - Create a Compute Engine instance and SSH into it to run your Python scripts.

5. **Install Required Python Packages**
   - Install the necessary Python packages on your compute instance:
     ```bash
     pip install -r requirements.txt
     ```

6. **Run the Data Pipeline**
   - Configure and execute the Mage data pipeline to load data into BigQuery.

7. **Visualize the Data**
   - Connect BigQuery to Looker Studio to create reports and dashboards.

## Usage

- Modify and run the Python scripts to process data as per your analysis requirements.
- Use Looker Studio to visualize the processed data and gain insights from it.
 
This project was implemented by following a tutorial, i do not own the rights to this code

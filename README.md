# Uber Data Engineering Project

## Introduction
Project created in educational purposes based on [Darshil Parmar YT tutorial](https://www.youtube.com/watch?v=WpQECq5Hx9g).<br>
Goal of this project is to analyze Uber Data from March 2016 using modern Data Engineer tools as GCP Storage, Python, Mage Data Pipipelina, BigQuery and Looker Studio.

## Technology Used
* Python 3.8
* Google Cloud Platform
  * Google Sorage
  * Compute Instance
  * BigQuery
  * Looker Studio
 * Mage Ai - pipeline tool
 
## Dataset
Data provided by TLC Trip Record Data for yellow and green taxi, records includes such attributes as pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. <br>
[Link to dataset](https://github.com/amatacz/uber-data-engineering/blob/main/uber_data.csv)

## Data Model
### Data stored in fact and dimension tables to get clear picture
<img src="https://github.com/amatacz/uber-data-engineering/blob/main/uber_data_model.png" style="max-width: 100%;"/>

## Data ETL and Analytics
Data has been extracted, transformed and loaded with Mage AI tool.
Query has been performed using BigQuery and loaded to LookerStudio to prepare interactive dashboard that helps anayze data such as revenue volume, locations and payment types.<br>
[Link to dashboard](https://lookerstudio.google.com/s/nPvVs8gSnMg)
<img src="https://github.com/amatacz/uber-data-engineering/blob/main/uber_dashboard.png" style="max-width: 100%;"/>


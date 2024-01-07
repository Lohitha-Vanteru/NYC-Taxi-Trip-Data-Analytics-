# NYC TAXI Trips Data Analytics Project

## Introduction

This project focuses on data analytics for Uber data using a variety of tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## Architecture
![architecture](https://github.com/Lohitha-Vanteru/Uber-Data-Analytics-/assets/113141006/fc3f36e2-ffae-43c7-a846-f235d72d00eb)

## Technology Used

- Programming Language: Python
- Google Cloud Platform:
  - Google Storage
  - Compute Instance
  - BigQuery
- Looker Studio
- Modern Data Pipeline Tool: [Mage](https://www.mage.ai/)

## Contribute

Feel free to contribute to this open-source project by visiting [mage-ai/mage-ai](https://github.com/mage-ai/mage-ai).

## Dataset Used

The project utilizes TLC Trip Record Data, including yellow and green taxi trip records, capturing various details such as pick-up/drop-off dates/times, locations, distances, fares, rate types, payment types, and passenger counts.

[Link to Dataset](https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv)
![data_model](https://github.com/Lohitha-Vanteru/Uber-Data-Analytics-/assets/113141006/81034f8f-5534-43d0-9096-c9bd0b0aa9ba)

More information about the dataset can be found on the [official TLC website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) and the [Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf).

## Steps Followed and Learnings

1. Extracted data and loaded it into Google Cloud Storage for further processing.
2. Transformed and modeled the data using fact and dimensional data modeling concepts using Python on Jupyter Notebook.
3. Orchestrated the ETL process/data pipeline on Mage and loaded the transformed data into Google BigQuery.
4. Developed a dashboard on Looker Studio.

### Learning Lessons

- Increased cloud instance resources (4 CPUs, 16GB memory) for improved performance.
- Addressed unexpected shutdowns in Mage by restarting SSH and creating a new firewall rule.

### Interesting Insights
![image](https://github.com/Lohitha-Vanteru/NYC-Taxi-Trip-Data-Analytics-/assets/113141006/fa82bbc4-ea92-45e8-8854-c3c3cc97547f)
#### DashBoard Link : 
[Link to Dashboard](https://lookerstudio.google.com/u/0/reporting/3a218e00-a785-471e-a65f-477fdd161022/page/eEOkD)
- Standard rate code generates the highest revenue.
- Trips to Newark result in the highest average tip at $11.
- Credit cards are the preferred payment mode (75% of transactions).
- One-person trips account for 66% of all recorded journeys.
- Top pickup location: Jackson Ave, near Queens Plaza station in Long Island City.
- Highest fare at 2 pm, suggesting a peak travel period, while the lowest fare is observed at 7 am during off-peak hours.


# NYC Taxi Data Engineering
The goal of this project is to showcase the steps required to build a data pipeline by Extract, Transform and Load, perform data analysis and build a dashboard.

The complete ETL files can be found at [mage](https://github.com/marcowong3/taxi-data-etl-pipeline/tree/main/mage_files)
## The Architecture
The image below shows the end-to-end process
<img src="./images/architecture.jpg">

## Tools Used
- Language: Python
- ETL: Google Cloud Platform - Compute Engine, Mage.ai,
- Data Warehouse: GCP - Cloud Storage
- Analytics: GCP - BigQuery
- Dashboard: Looker

## The Data
The data contains 100,000 records of NYC Taxi rides. 
<br /> Some key features include: VendorID, Trip Distance, Payment Type, Pickup/Dropoff Latitude/Longitude, Tip Amount, Toll Amount and Total Amount.
<br /> <br /> Original data source can be found at [NYC Taxi Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
<br /> CSV data can be found at [data](https://github.com/marcowong3/taxi-data-etl-pipeline/tree/main/data)
<br /> Data Dictionary can be found at [dictionary](https://github.com/marcowong3/taxi-data-etl-pipeline/blob/main/images/data_dictionary.pdf)

## The Dataset Framework
<img src="./images/data_framework.jpeg">

## Dashboard
Looker dashboard can be found at [dashboard](https://lookerstudio.google.com/s/rMp409816po)

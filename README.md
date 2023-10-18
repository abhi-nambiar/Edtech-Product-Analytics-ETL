# Edtech-Product-Analytics-ETL

## Project Description:
Udemy aimed to refine their email marketing strategies using data-driven insights. The focus was on understanding user engagement metrics like email sent, open, click, etc., which were captured by Hubspot.

## Objective:
The main goal was to leverage this engagement data to enhance the effectiveness of Udemy's email campaigns. This involved gaining a deeper understanding of how users interacted with the emails.

## Tools and Technologies:
Google Cloud Platform (GCP): Provided the infrastructure and services for data processing and storage.
Apache Nifi: Used for data ingestion and orchestration, automating the movement of data through the entire pipeline.
Google Cloud Storage (GCS): Stored the incoming data from Hubspot.
Dataproc: Used for data processing tasks similar to Amazon EMR.
BigQuery: A serverless data warehouse used for analysis.

## Implementation:

Data Model:
![image](https://github.com/abhi-nambiar/Edtech-Product-Analytics-ETL/assets/123143416/607d1926-7626-42a4-894d-7408e868889f)

![image](https://github.com/abhi-nambiar/Edtech-Product-Analytics-ETL/assets/123143416/252af063-0c80-47f2-a90e-b27359ffc875)

Data Generation: Sample Data was generated using Mockaroo API
Data Ingestion: Hubspot-generated user engagement data was collected and stored in Google Cloud Storage using Apache Nifi.
Data Processing: Dataproc, functioning as a virtual cluster, was employed to run scripts and process the data. This was where the heavy lifting of data transformation and analysis took place.
Data Storage: The processed data was then loaded into BigQuery. This served as the centralized data warehouse where comprehensive analysis could be conducted.

## Conclusion:
Through this implementation, data was made available to data scientists to perform analysis and help Udemy streamline their email marketing efforts. The tools and technologies provided a robust framework for not only analyzing user engagement but also deriving actionable insights to optimize their campaigns for better performance and user interaction.

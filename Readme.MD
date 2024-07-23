A robust pipeline designed to efficiently ingest, transform, and load aviation data into Redshift.

Tech Stack:
1.	One dimension table Airport port
2.	In S3 daily basis flight data will arrive
3.	S3 is the data lake
4.	Use event bridge rule as soon as file landing in s3 folder
5.	Step function where orchestrated 
6.	Glue crawler
7.	Glue job
8.	Readshift 
9.	SNS for notifications


                                     Aero-Data-Ingestion Pipeline
![Airline_data_ingestion_AWS drawio](https://github.com/user-attachments/assets/3fd3402e-1c9d-4a52-b51e-40bc58af6836)

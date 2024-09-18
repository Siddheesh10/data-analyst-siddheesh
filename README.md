# data-analyst-siddheesh
PARKING TICKETS ANALYSIS USING AWS CLOUD COMPUTING
</br>
# Project Description
This project analyzes the City of Vancouver parking ticket data for 2023 and 2024. Using AWS cloud services, the data was processed, cleaned, and analyzed to uncover insights into parking violations, enforcement patterns, and compliance rates.
**Project Title:** Parking Tickets Analysis for the City of Vancouver Using AWS Cloud Services

**Objective:** To perform a detailed analysis of parking ticket data to:
1.	Identify patterns of parking violations.
2.	Analyze enforcement efficiency.
3.	Determine compliance rates and reasons behind violations.

**Dataset:** The dataset consists of two parking ticket records:

**Parking Tickets 2023:** 100 entries detailing the block, infraction type, bylaw section, status, and dates.

**Parking Tickets 2024:** 100 entries similar to the 2023 dataset, focusing on the same details.

# Methodology
**Data Storage:** Utilized AWS S3 for storing datasets in separate folders for 2023 and 2024.</br>
**Data Cleaning & Preparation:** AWS Glue DataBrew was used to clean the dataset, removing duplicates and ensuring uniformity.
</br>
**Data Pipeline:** Created a weekly-updating ETL pipeline using AWS Glue and stored processed data in Amazon Redshift.
</br>
**Data Analysis:** Conducted SQL-based analysis using Amazon Athena to identify trends in violations, hotspots for tickets, and compliance behavior.
</br>
**Data Security:** Implemented encryption using AWS KMS, ensuring data confidentiality and integrity.
</br>
**Data Monitoring:** Used AWS CloudWatch and CloudTrail for resource monitoring, tracking user activity, and ensuring data governance.

# Tools and Technologies
**AWS Services:**
1.	Amazon S3
2.	AWS Glue
3.	Amazon Redshift
4.	Amazon Athena
5.	AWS CloudWatch
6.	AWS CloudTrail
7.	AWS KMS

# Data Analysis:
1.	Python (Pandas, NumPy)
2.	SQL (Amazon Athena)
3.	AWS Glue DataBrew for data cleaning and preparation


# Key Features
•	**Descriptive Analysis:** Investigated peak times for violations, common infraction types, and geographical locations with high violation rates.
</br>
•	**Diagnostic Analysis:** Explored reasons behind high violation rates in certain areas and factors affecting compliance with ticket payments.
</br>
•	**Security & Data Protection:** Data was encrypted using AWS KMS, ensuring protection against unauthorized access.
</br>
•	Versioning and replication rules for S3 buckets provided additional data recovery options.


# Deliverables
•	**Cleaned Datasets:** 2023 and 2024 parking ticket datasets, cleaned and stored in Amazon S3.
</br>
•	**SQL Queries:** SQL queries used to analyze the parking ticket data in Amazon Athena.
</br>
•	**ETL Pipeline:** A weekly automated ETL pipeline for continuous data ingestion and transformation.
</br>
•	**Security & Monitoring Dashboards:** AWS CloudWatch and CloudTrail dashboards are used to track resource usage, data integrity, and security metrics.


# Cost & Sustainability
•	**Annual Cost:** Estimated at USD 209.55 for AWS services. For one dataset.
</br>
•	**Optimization:** Utilized cost-effective AWS services such as serverless computing (Athena, Glue) and S3 storage.

# CONCLUSION
This project provided valuable insights into parking violations and compliance behavior in the City of Vancouver. By leveraging AWS cloud services, I was able to efficiently store, process, analyze, and secure large datasets while ensuring scalability and data governance.

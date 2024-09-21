# data-analyst-siddheesh
# PARKING TICKETS ANALYSIS USING AWS CLOUD COMPUTING 
# Project Description
This project analyzes the City of Vancouver parking ticket data for 2023 and 2024. Using AWS cloud services, the data was processed, cleaned, and analyzed to uncover insights into parking violations, enforcement patterns, and compliance rates.

**Project Title:** Parking Tickets Analysis for the City of Vancouver Using AWS Cloud Services

**Objective:** To perform a detailed analysis of parking ticket data to:
1.	Identify patterns of parking violations.
2.	Analyze enforcement efficiency.
3.	Determine compliance rates and reasons behind violations.

**Dataset:** The dataset consists of two parking ticket records:

![image](https://github.com/user-attachments/assets/0db19578-1d16-48bd-a1a7-4dc6e30dfb08)

**Parking Tickets 2023:** 100 entries detailing the block, infraction type, bylaw section, status, and dates.

**Parking Tickets 2024:** 100 entries similar to the 2023 dataset, focusing on the same details.

# Methodology
**Data Storage:** Utilized AWS S3 for storing datasets in separate folders for 2023 and 2024.
![image](https://github.com/user-attachments/assets/9bedf818-1845-4175-b9fe-c1673660be70)

**Data Cleaning & Preparation:** AWS Glue DataBrew was used to clean the dataset, removing duplicates and ensuring uniformity.

**Data Pipeline:** Created a weekly-updating ETL pipeline using AWS Glue and stored processed data in Amazon Redshift.
![image](https://github.com/user-attachments/assets/7500fcf4-08c7-425a-bb17-5e57dc596eb6)

**Data Analysis:** Conducted SQL-based analysis using Amazon Athena to identify trends in violations, hotspots for tickets, and compliance behavior.
![image](https://github.com/user-attachments/assets/59a0cca6-c956-491d-b880-814275ae1275)

**Data Security:** Implemented encryption using AWS KMS, ensuring data confidentiality and integrity.
![image](https://github.com/user-attachments/assets/e6af2027-94e0-4dbf-8dc8-538839b2bed3)
Key Management Services (KMS) applied on Parking Tickets:
![image](https://github.com/user-attachments/assets/76eb25fe-ba5e-4cb9-b5a0-c5726d6c50b7)

**Data Monitoring:** Used AWS CloudWatch and CloudTrail for resource monitoring, tracking user activity, and ensuring data governance.
Dashboard:
![image](https://github.com/user-attachments/assets/af672af8-9082-42be-9df1-d5d82fa065f8)
Setting an Alarm:
![image](https://github.com/user-attachments/assets/ef7f76cd-3d17-46f0-bb6f-e51ce199770f)

# Tools and Technologies
**AWS Services:**
![image](https://github.com/user-attachments/assets/32da2a0c-1637-40e9-8f16-8364abd0652d)

1.	Amazon S3
2.	AWS Glue
3.	Amazon Redshift
4.	Amazon Athena
5.	AWS CloudWatch
6.	AWS CloudTrail
7.	AWS Key Management Service (KMS)
8.	AWS IAM

# Data Analysis:
1.	Python (Pandas, NumPy)
2.	SQL (Amazon Athena)
3.	AWS Glue DataBrew for data cleaning and preparation


# Key Features
•	**Descriptive Analysis:** Investigated peak times for violations, common infraction types, and geographical locations with high violation rates.

•	**Diagnostic Analysis:** Explored reasons behind high violation rates in certain areas and factors affecting compliance with ticket payments.

•	**Security & Data Protection:** Data was encrypted using AWS KMS, ensuring protection against unauthorized access.

•	Versioning and replication rules for S3 buckets provided additional data recovery options.


# Deliverables
•	**Cleaned Datasets:** 2023 and 2024 parking ticket datasets, cleaned and stored in Amazon S3.

•	**SQL Queries:** SQL queries used to analyze the parking ticket data in Amazon Athena.

•	**ETL Pipeline:** A weekly automated ETL pipeline for continuous data ingestion and transformation.

•	**Security & Monitoring Dashboards:** AWS CloudWatch and CloudTrail dashboards are used to track resource usage, data integrity, and security metrics.


# Cost & Sustainability
•	**Annual Cost:** Estimated at USD 209.55 for AWS services. For one dataset.

•	**Optimization:** Utilized cost-effective AWS services such as serverless computing (Athena, Glue) and S3 storage.

# CONCLUSION
This project provided valuable insights into parking violations and compliance behavior in the City of Vancouver. By leveraging AWS cloud services, I was able to efficiently store, process, analyze, and secure large datasets while ensuring scalability and data governance.



<br /><br /><br /><br />
# TRAINING RECORDS - PROGRAM REVIEW ANALYSIS USING AWS CLOUD COMPUTING

# Project Description
This project analyzes training records data from the UCW Data Center, focusing on the academic domain. The data was processed, cleaned, and analyzed using AWS cloud services to uncover insights into program efficiency, student performance, and review trends.

# Project Title
Training Records Analysis for UCW Using AWS Cloud Services

# Objective
**To perform a comprehensive analysis of training records to:**
•	Identify key academic performance trends.
•	Analyze training efficiency and areas for improvement.
•	Understand review patterns and academic compliance.

# Dataset
**The dataset consists of:**
**•	Training Records 2024:** Contains detailed entries of academic training records for 2024, including program performance metrics, student feedback, and review dates.

# Methodology

**1.	Data Storage:** The training records data is securely stored in AWS S3, organized for efficient retrieval and analysis.

**2.	Data Cleaning & Preparation:** AWS Glue DataBrew was used for cleaning, including removing duplicates, correcting inconsistencies, and ensuring a uniform structure.

**3.	Data Pipeline:** A weekly updating ETL pipeline was created using AWS Glue, with the cleaned data stored in Amazon Redshift for further analysis.

**4.	Data Analysis:** SQL queries in Amazon Athena were used to identify academic performance trends, highlight improvement areas, and analyze training records data.

**5.	Data Security:** Encryption was applied using AWS KMS to ensure data privacy and compliance with academic standards.

**6.	Data Monitoring:** AWS CloudWatch and CloudTrail were employed to monitor resource usage and ensure data governance and security.

# Tools and Technologies
**•	AWS Services:**
o	Amazon S3
o	AWS Glue
o	Amazon Redshift
o	Amazon Athena
o	AWS CloudWatch
o	AWS CloudTrail
o	AWS KMS

# •	Data Analysis
o	Python (Pandas, NumPy)
o	SQL (Amazon Athena)
o	AWS Glue DataBrew for data cleaning and preparation

# Key Features
1.	Descriptive Analysis: Investigated performance metrics, review frequency, and key feedback points in the training records.
2.	Diagnostic Analysis: Explored factors affecting student performance and compliance with academic standards.
3.	Security & Data Protection: Training records data was encrypted using AWS KMS, with versioning and replication rules for S3 buckets providing data recovery and security.

# Deliverables

**•	Cleaned Datasets:** 2024 training records stored in Amazon S3, ready for further academic analysis.

**•	SQL Queries:** SQL scripts to query the training records data using Amazon Athena.

**•	ETL Pipeline:** A weekly automated ETL pipeline to keep training records updated and clean.

**•	Monitoring Dashboards:** AWS CloudWatch dashboards are used to track resource usage and ensure data security.


# Cost & Sustainability
•	Annual Cost: Estimated at approximately USD 40 for AWS services.
•	Optimization: Utilized cost-efficient services like AWS Glue for ETL and Amazon S3 for storage.

# CONCLUSION
This project provided valuable insights into the academic performance and review processes at UCW. By leveraging AWS cloud services, training records data was stored, processed, analyzed, and secured in a scalable and efficient way, enhancing decision-making for future academic strategies.


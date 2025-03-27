# data-analyst-malati
# 📊 Data Wrangling Analysis

## 📌 Project Title
**Data Wrangling Analysis of Academic Institutions Implementation**

---

## 📝 Project Description
This project utilizes cloud computing services to execute large-scale data wrangling operations on Academic Institutions data. It relies on AWS Glue along with Amazon S3 and other cloud services to produce precise and useful aggregated data through data cleaning and transformation of multiple city-related datasets.

---

## 🎯 Objective
To carry out automated and scalable data wrangling on Academic Institutions (Ethics Procedures) datasets using cloud computing services for cost-effective and efficient data processing.

---

## 📚 Background
Academic Institutions maintain full ethics protocols, which include zoning, land use, infrastructure, and municipal service data. Data wrangling improves the quality, scalability, and automation of this data, enhancing its utility in research and policy-making.

---

## 🧾 Dataset
University ethics procedures datasets include:
- Zoning and land use maps
- Property boundaries
- Road networks and infrastructure
- Population, business activity, crime, and environmental data

---

## 🔍 Methodology

### 1. Data Ingestion & Collection
- Store raw data in Amazon S3
- Use AWS Glue Crawlers to detect schema and populate the AWS Glue Data Catalog

### 2. Data Assessment
- Use AWS Glue DataBrew to check for missing values and duplicates
- Document inconsistencies and data types
- Log issues with Amazon CloudWatch

### 3. Data Cleaning
- Impute missing values using AWS Glue
- Standardize categories with AWS Lambda

### 4. Data Transformation
- Transform types using AWS Glue ETL scripts
- Generate new metrics (e.g., average traffic volume)
- Summarize trends (monthly/quarterly)

### 5. Data Consolidation
- Connect datasets using unique IDs
- Combine sources and run DataBrew jobs

### 6. Documentation & Validation
- Record process in AWS Glue Data Catalog
- Validate data using Amazon Athena

---

## 🧰 Tools & Technologies
- **Data Storage:** Amazon S3  
- **Data Wrangling:** AWS Glue, AWS Glue DataBrew, AWS Lambda  
- **Validation:** AWS Glue Data Catalog, Amazon Athena  
- **Monitoring:** Amazon CloudWatch, AWS CloudTrail  

---

## 📦 Deliverables
- Cleaned and transformed dataset in Amazon S3  
- Overview of wrangling processes  
- Amazon QuickSight visualizations: air quality, traffic, urban services  
- Problems identified & solutions applied  

---

## 🗓️ Project Timeline
**Total Duration:** 4 Weeks

---

## ✅ Expected Outcomes
- Enhanced data quality for planning and public service improvements  
- Scalable, automated workflows via AWS  
- Accurate data for informed infrastructure planning  

# screenshots
<img src="Picture.12.png">

# 📋 Data Quality Control Analysis

## 📌 Project Title
**Data Quality Control Measures of Academic Institutions Implementation**

---

## 📝 Project Description
This project develops a Data Quality Control (DQC) framework for university ethics procedure data using cloud technologies. AWS services ensure the reliability, consistency, and accuracy of data needed for zoning, infrastructure, and development.

---

## 🎯 Objective
To apply an end-to-end DQC system to Academic Institution ethics data using cloud solutions to improve data integrity for planning and management.

---

## 📚 Background
Academic ethics data includes zoning, land use, and infrastructure records. However, it suffers from format issues, missing values, and inconsistencies. These flaws affect research, service delivery, and compliance. This project addresses such issues using AWS automation and monitoring services.

---

## 🎯 Scope
- **Data Cleansing:** Remove duplicates automatically  
- **Data Profiling:** Evaluate data quality and readiness  
- **Data Validation:** Enforce rules for consistency  
- **Monitoring & Reporting:** Create dashboards for quality metrics  
- **Training:** Equip staff to uphold data standards  

---

## 🔍 Methodologies

- **Data Profiling:** AWS Glue DataBrew to assess accuracy, consistency, and anomalies  
- **Data Cleaning:** AWS Glue ETL for formatting and duplicates  
- **Monitoring:** AWS CloudWatch alerts for anomalies  
- **Reporting:** Auto-generate quality reports  
- **Metrics:** Track missing values, duplicates, schema violations  

---

## 📦 Tools & Technologies

- **Storage:** Amazon S3  
- **Governance & Validation:** AWS CloudTrail, AWS Lambda  
- **Profiling & Cleansing:** AWS Glue, DataBrew  
- **Monitoring & Reporting:** AWS CloudWatch  

---

## 📋 Deliverables
- High-quality ethics dataset in S3  
- Comprehensive data quality report  
- Monitoring dashboard (missing data, errors, geo-inconsistencies)  
- Staff training content and workshops  

---

## 🗓️ Project Timeline
**Total Duration:** 4 Weeks

  

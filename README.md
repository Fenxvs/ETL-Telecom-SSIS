# 📞 ETL Pipeline for Telecom Call Detail Records (CDRs)

This repository contains an **SSIS-based ETL solution** for automating the ingestion, transformation, and storage of telecom call detail records (CDRs). The pipeline is designed to handle frequent raw data ingestion while ensuring **data quality, consistency, and auditability**.

---

## ✨ Key Features  

- ⚡ **Automated Ingestion**: Detects and loads CSV files generated every 5 minutes.  
- 🧹 **Data Transformation & Validation**:  
  - Validates identifiers (**IMSI, CELL, LAC**)  
  - Enriches records with **subscriber_id** via reference table joins  
  - Extracts **TAC** and **SNR**, validates timestamp formats  
- 🚨 **Error Handling**: Captures, logs, and stores rejected records for later review  
- 📂 **File Management**: Archives processed files to maintain integrity and prevent duplication  

---

## 📊 Outcome  

The pipeline ensures:  
- ✅ Clean, validated CDRs stored in a relational database  
- ⚙️ Reliable automation of workflows with SSIS  
- 📝 Full audit trail for rejected records  
- 📈 Scalable foundation for telecom data analysis and reporting

  <img width="1536" height="253" alt="image" src="https://github.com/user-attachments/assets/e2e9e4c7-87e7-4879-acd4-8d25ccc8738b" />


---

## 🛠️ Tools & Technologies  

- 🖥️ **SQL Server Integration Services (SSIS)** – for building ETL workflows  
- 🗄️ **SQL Server Management Studio (SSMS)** – for managing the database  
- 📑 **CSV** – as the raw data input format  
- 🏗️ **SQL Server** – relational database for storing processed data  

---
<div align="center">
<img src="https://github.com/user-attachments/assets/25e8230a-a40b-4a7c-9546-64b963edcba9" alt="SSIS Data Flow Task - Part 1" width="450"/>
<img src="https://github.com/user-attachments/assets/5104ea0c-c22e-4b4c-a8c5-27de3072a3c5" alt="SSIS Data Flow Task - Part 2" width="368"/>
</div>

## 🚀 Skills Demonstrated  

- Data pipeline development  
- Data quality & validation techniques  
- Automated workflows with SSIS  
- Relational database integration in a telecom context  

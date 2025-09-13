# ETL-Telecom-SSIS
An SSIS-based ETL solution that automates ingestion, transformation, and storage of telecom CDRs. CSV files generated every 5 minutes are validated, enriched with subscriber data, and transformed (TAC/SNR extraction, timestamp checks). Invalid records are logged, and processed files archived to ensure clean, reliable data.

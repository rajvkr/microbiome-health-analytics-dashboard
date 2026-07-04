# 🦠 Microbiome Health Analytics Dashboard

An end-to-end Power BI solution developed to analyze microbiome sequencing data and transform complex microbial information into interactive business insights.

## 📌 Business Problem

Microbiome sequencing reports contain thousands of microbial records across multiple taxonomic levels, making manual interpretation difficult. This dashboard enables researchers to monitor microbial diversity, pathogen prevalence, beneficial bacteria, functional bacterial groups, and overall microbiome health for each biological sample.

---

## 🛠 Tech Stack

- Power BI
- Power Query (ETL)
- DAX
- Excel

---

## ⚙️ ETL & Data Preparation

- Automated ingestion of multiple Excel reports using **Folder Connector**.
- Standardized column names across all files.
- Applied **Fill Down / Fill Up** logic to populate missing sample metadata.
- Replaced missing taxonomy values with **"Unclassified"**.
- Validated and converted data types for reliable analysis.

---

## 📊 Key DAX Implementations

- Dynamic **Shannon Diversity Index** calculation.
- Top 10 Beneficial Species ranking using `TOPN()`.
- Dynamic KPI measures for:
  - Pathogen Load
  - Beneficial Abundance
  - Vibrio Load
  - Virus Abundance
  - Toxic Blue-Green Algae
  - Ammonia & Nitrite Oxidisers

---

## 📈 Dashboard Highlights

- Interactive Sample-wise Analysis
- Biodiversity Assessment
- Taxonomic Distribution (Phylum/Class)
- Pathogen Risk Monitoring
- Beneficial Bacteria Analysis
- Functional Group Monitoring
- Executive Summary & Key Findings

---

## 💡 Key Features

✔ Automated data ingestion

✔ Dynamic DAX calculations

✔ Interactive executive reporting

✔ Scientific KPI visualization

✔ Sample-level microbiome health analysis

---

## 🚀 Future Enhancements

- AI-generated Executive Summary using Microsoft Copilot / Azure OpenAI
- Dynamic Key Findings using DAX
- Overall Microbiome Health Score
- Risk Classification (Healthy / Moderate / High Risk)

---

## 📷 Dashboard Preview

> Add dashboard screenshots here.

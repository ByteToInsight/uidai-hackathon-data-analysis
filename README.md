# Aadhaar Data Analysis – Hackathon Project

This repository contains a refactored, modular data analysis pipeline developed as part of a hackathon, focused on analyzing Aadhaar-related datasets including enrolment, biometric, and demographic data.

The project demonstrates real-world data cleaning, integration of multiple datasets, and exploratory analysis on large-scale public data.

---

## Project Overview
- Context: Hackathon-based data analysis project  
- Domain: Public sector / government data  
- Objective: Extract actionable insights from Aadhaar enrolment and usage data using a clean, reproducible analysis pipeline  

The original analysis was implemented as a single script and has been refactored into modular notebooks for better readability, maintainability, and public sharing.

---

## Datasets
- Source: Government of India open-data portal (public datasets)
- Types:
  - Enrolment data
  - Biometric-related data
  - Demographic data
- Scale (original analysis): ~100,000+ records across multiple files
- Nature: Non-sensitive, anonymized public data

### Sample Data
The `data/` directory contains **representative sample datasets (~100 rows each)** created to allow the notebooks to run out-of-the-box.  
The analysis logic is designed to scale to the full datasets with compatible schemas.

---

## Project Structure
- **01_data_overview.ipynb**  
  Initial data loading, schema inspection, and validation across multiple datasets.

- **02_data_cleaning.ipynb**  
  Data cleaning, standardization, aggregation, and merging into a unified master dataset.

- **03_eda_insights.ipynb**  
  Exploratory Data Analysis (EDA), trend analysis, exploratory K-Means clustering (pattern discovery), and anomaly detection.

- **data/**  
  Representative sample datasets for enrolment, biometric, and demographic data.

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- scikit-learn
- Jupyter Notebook

---

## Key Takeaways
- Built a scalable EDA pipeline for multi-file government datasets
- Integrated enrolment, biometric, and demographic data into a unified analysis
- Identified trends, anomalies, and patterns under hackathon time constraints
- Refactored legacy analysis into clean, modular notebooks suitable for collaboration and reuse

---

## Setup
1. Install dependencies:
   ```bash
   pip install -r requirements.txt


2. Run notebooks in order:

      01_data_overview.ipynb

      02_data_cleaning.ipynb

      03_eda_insights.ipynb

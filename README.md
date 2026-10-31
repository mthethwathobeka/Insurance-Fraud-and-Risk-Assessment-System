# Insurance Fraud and Risk Assessment System

An advanced data analytics and visualization solution built using Power BI, DAX, and Power Query to evaluate insurance claim risk and streamline fraud investigation workflows.

## Project Overview
This project processes and analyzes a 53,503-record insurance dataset to identify potential risk indicators and prioritize claims for review. By combining rigorous data cleansing, advanced DAX modelling, and interactive dashboards, the system helps risk management teams efficiently target investigations.

## Key Features & Architecture

* **Data Cleaning & Transformation (Power Query):** Cleaned, transformed, and validated 53,503 records by verifying data types, addressing missing and duplicate values, and flagging 2,247 records with invalid policy dates using a custom Data Quality Flag.
* **Feature Engineering:** Created structured derived fields—including Record ID, Age Group, Credit Score Category, Policy Duration, and Coverage to Income—to enhance dashboard filtering and exploratory depth.
* **Rules-Based Risk Scoring & Fraud Logic (DAX):** Developed a transparent rules-based risk model combining six distinct indicators to classify records into Low, Medium, or High risk bands, alongside a Potential Fraud Indicator to prioritize records for human review.
* **Interactive Power BI Report:** Designed a comprehensive three-page dashboard featuring:
  * **Exploratory Analysis:** Deep dive into dataset trends and characteristics.
  * **Risk Assessment:** A prioritized investigation queue for high-risk files.
  * **Executive Dashboard:** High-level overview utilizing KPI cards, slicers, and seamless page navigation.
* **Validation & Testing:** Performed rigorous record-count, claim-total, and risk-band reconciliations against the source data to guarantee reporting accuracy.
* **Documentation & Limitations:** Documented project constraints (including the use of synthetic data and lack of confirmed fraud labels) and recommended threshold calibration against confirmed real-world outcomes.

## Tech Stack
* **Business Intelligence & Reporting:** Power BI, Power Query, DAX
* **Data Concepts:** Data Cleansing, Data Validation, Exploratory Data Analysis, Risk Modelling, Fraud Analytics

## Dashboard Visualation
# Insurance Fraud and Risk Executive Dashboard
<img width="1377" height="772" alt="image" src="https://github.com/user-attachments/assets/29a0dd7b-9b8e-41c2-bbce-0c325430d560" />


## How to Use
1. Clone the repository to your local machine.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. Review the Power Query transformation steps and DAX measures implemented for risk categorization and KPI tracking.

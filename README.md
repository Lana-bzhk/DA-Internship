# CRM ETL

Python pipeline for cleaning CRM export and preparing data for Power BI.

---

## Pipeline

* clean phone/email
* extract telegram
* merge notes
* clean finance
* merge UTM
* remove raw source columns

---

## Key logic

Lead_Key = Phone → Email → ID

Is_Duplicate = True / False

---

## Data Cleaning

* remove empty columns
* remove technical columns
* remove raw UTM/referrer columns after merge

---

## Input

crm_output.csv

---

## Output

powerbi_leads_clean.csv

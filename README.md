# MedDosageValidator-LLM
Final Project for AI in Healthcare at UT Austin MSAI Spring 2025

According to the NIH, medication errors cause 1 of every 854 inpatient deaths and cost the nation $2 billion in additional hospital expenses. Our project aims to automatically detect discrepancies between dosages prescribed in free-text clinical notes and those recorded in structured medication administration records. By leveraging Natural Language Processing (NLP) and Large Language Models (LLMs), we've developed a system that can potentially help prevent medication errors and improve patient safety. 

# Repository Contents
- HRP_Team4_Spring2025_Final: Jupyter notebook containing all code for data processing, model training, and evaluation
- Report.pdf: ACM-style research paper detailing our methodology and findings

# Dataset
This project uses the Medical Information Mart for Intensive Care III (MIMIC-III) dataset, focusing specifically on:
- Structured medication administration records (inputevents_mv)
- Free-text clinical notes (noteevents)
- Drug-specific information (d_items)

For our study, we selected Fentanyl as the focus drug due to its:
- High prescription frequency
- High risk if incorrectly dosed
- Consistency in unit of measurement

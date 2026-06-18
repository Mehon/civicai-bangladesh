# civicai-bangladesh
Bilingual NLP framework for citizen complaint classification — IEEE RAAICON 2026

# Bilingual AI-Powered Citizen Service Request Classification
### A Lightweight NLP Approach for Developing Nations

**Paper:** Submitted to IEEE RAAICON 2026  
**Author:** Enamul Haque Mehon, AEVYRA, Dhaka, Bangladesh  
**Status:** Under Review

---

## Overview
This repository contains the complete code, datasets, and results 
for the paper "Bilingual AI-Powered Citizen Service Request 
Classification for Smart Governance."

We propose a bilingual NLP framework classifying citizen complaints 
into 7 municipal departments using 4 models across English and Bengali.

## Results Summary

| Model | Language | Accuracy |
|-------|----------|----------|
| Naive Bayes | English | 70.13% |
| Logistic Regression | English | 74.03% |
| DistilBERT | English | 88.31% |
| BanglaBERT | Bengali | 80.95% |

## Dataset
- English: 385 samples across 7 categories
- Bengali: 210 samples across 7 categories
- Both datasets available in /data/

## How to Run

### 1. Install requirements
pip install -r requirements.txt

### 2. Create datasets
python code/create_dataset.py
python code/create_bangla_dataset.py

### 3. Run models
python code/model1_naive_bayes.py
python code/model2_logistic_regression.py
python code/model3_distilbert.py
python code/model4_banglabert.py

### 4. Generate comparison chart
python code/model_comparison_chart.py

## Citation
If you use this dataset or code, please cite:
[Citation will appear here after publication]

## Institution
AEVYRA (Aevum Empowered Visionary Youth for Reform & Advancement)  
Dhaka, Bangladesh  
www.aevyra.institute

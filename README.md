# AI-Powered-Smart-Email-Classifier
AI Powered Smart Email Classifier for Enterprises

## Milestone 1: Data Collection & Preprocessing
## Overview

This project builds an AI-powered email classification system for enterprises. Milestone 1 focuses on collecting and cleaning email datasets for training machine learning models.

## Project Structure

```
Infosys/
├── Dataset/
│   ├── Classification_Dataset/
│   │   ├── Raw_Dataset/              # Original data files
│   │   ├── Cleaning code/            # Cleaning scripts
│   │   └── cleaned_Dataset/          # merged_cleaned_dataset.csv
│   │
│   └── Urgency_Dataset/
│       ├── Raw_Dataset/              # train.csv, test.csv, validation.csv
│       ├── Cleaned_Dataset/          # Cleaned versions
│       └── data_cleaning.py          # Cleaning script
│
└── README.md
```


## Usage

**Classification Dataset Cleaning:**
```bash
cd Datset/Classification_Dataset/Cleaning\ code/
python clean_complaint.py
python clean_request.py
python clean_promotion.py
python clean_social_media.py
python clean_spam.py
python merge_cleaned_datasets.py
```

**Urgency Dataset Cleaning:**
```bash
cd Datset/Urgency_Dataset/
python data_cleaning.py


## Milestone 2: Email Categorization Engine

## Overview

Milestone 2 focused on developing an NLP-based classification system to categorize emails into **Complaint**, **Request**, **feedback**, **Spam**.

### 2. Transformer Fine-Tuning (DistilBERT)
Fine-tuned a pre-trained **DistilBERT** model for state-of-the-art performance.
- **Model**: `distilbert
rule based logic
**Run DistilBERT Training:**
```bash
python bert_finetuning.py


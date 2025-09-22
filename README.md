# B13.2_PGNO260_G10

📰 Fake OR Real News Detection Project

📌 Project Overview

This project focuses on building a pipeline to detect Fake News vs Real News using Natural Language Processing (NLP) techniques.
We use a publicly available dataset containing real and fake news articles.
The workflow includes:

->Dataset Collection & Import
->Data Cleaning & Preprocessing
->Feature Engineering (word/char counts, TF-IDF, etc.)
->Exploratory Data Analysis (EDA) & Visualization
->Integrated Group Pipeline for Final Preprocessed Dataset
->Each group member contributes with their assigned preprocessing step, documented in individual Jupyter notebooks.


📂 Dataset Details

Source Files:
True.csv → Real news articles
Fake.csv → Fake news articles

Columns:
title → Headline of the news
text → Full body text of the article

label → Added column (“REAL” or “FAKE”)

Size:
Real News: ~21,000 articles
Fake News: ~23,000 articles

Final Output File:
preprocessed_news.csv → contains cleaned text (clean_text) and labels (label).
Stored inside results/outputs/.


Group member roles:

01.Data Set Collection and Import (IT24103775 -Fernando B.S.C)
02.Data Cleaning (IT24103280 -Herath H.M.S.R)
03.Text Preprocessing (IT24103525 - Semasinghe S.M.B.C)
04.Feature Creation (IT24103516 -Herath A.M.O.S)
05.Exploratory Data Analysis (IT24103792 -Peiris W.S.V)
06.Visualization Of Text Patterns (IT24103303 -Warakapola A.A.M)

▶️ How to Run the Project (Jupyter Notebook)
1️⃣ Setup

Make sure you have Python 3.8+ and the following libraries installed:

code: pip install pandas numpy matplotlib seaborn scikit-learn nltk

2️⃣ Run Individual Notebooks

Each member’s work is stored in:

>notebooks/IT_Number_Preprocessing_technique.ipynb

Open and run the notebook assigned to each member.

3️⃣ Run Group Pipeline

Run the integrated pipeline:

> jupyter notebook notebooks/group_pipeline.ipynb

This will:

-> Load the dataset (data/raw/)
-> Apply preprocessing (clean_text)
-> Save the preprocessed dataset in results/outputs/preprocessed_news.csv

Generate visualizations inside results/eda_visualizations/

4️⃣ View Outputs

📂 results/outputs/ → Final preprocessed dataset(s)
📂 results/eda_visualizations/ → Plots & charts
📂 results/logs/ → (Optional) Execution logs

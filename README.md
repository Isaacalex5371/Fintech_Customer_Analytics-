# Fintech_Customer_Analytics-
Analysis of Ethiopian banking apps reviews for Omega Consultancy.


**Project by:** yishak alemayehu
**Role:** Data Analyst / Data Engineer  
**Context:** Omega Consultancy - Week 2 Challenge

## 📌 Project Overview
This project focuses on analyzing customer satisfaction for the top three financial apps in Ethiopia: **Commercial Bank of Ethiopia (CBE)**, **Bank of Abyssinia (BOA)**, and **Dashen Bank**.

By scraping real-world user reviews from the Google Play Store, performing advanced Natural Language Processing (NLP), and utilizing data engineering best practices, this project identifies key drivers of user retention and pain points.

## 🏢 Business Objective
**Omega Consultancy** aims to support banking partners in improving their mobile application ratings and user retention. The goals of this analysis were to:
1.  **Quantify Sentiment**: Move beyond star ratings to understand the *emotion* behind text.
2.  **Identify Themes**: Cluster feedback into actionable categories (e.g., "Login Issues", "Transaction Speed").
3.  **Data Pipeline**: Build a reproducible pipeline from scraping to analysis.

---

## 📂 Project Structure
```bash
Fintech_Customer_Analytics/
│
├── data/
│   ├── raw_reviews.csv      # Original data scraped from Play Store
│   └── cleaned_reviews.csv  # Processed data ready for analysis
├── notebooks/
│   └── analysis.ipynb       # Jupyter notebook for visualization & experiments
├── src/
│   ├── scraper.py           # Script to collect reviews using google-play-scraper
│   ├── cleaner.py           # Data cleaning & preprocessing logic
│   └── analysis.py          # Sentiment analysis & thematic clustering script
├── venv/                    # Virtual Environment
├── .gitignore               # Git ignore rules
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
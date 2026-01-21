# Amazon-Product-Review-Performance-and-Sentiment-Intelligence
 1. Performing ETL(Extract- Transform - Load), and moving data from a local CSV file into Azure SQL Database using Python.              2. Multi-class Logistic Regression              3. Confusion Matrix for Multi-class classifier              4. TF-IDF Word Cloud for Multi-class scenario
### About project

**Category:**

Data Analytics | Sentiment Analysis

**Tech Stack:**

Python, Azure SQL, Pandas, Matplotlib, Seaborn, NLP

**GitHub:**

https://github.com/Nishigandha-Wankhade/Amazon-Product-Review-Performance-and-Sentiment-Intelligence/tree/main

## Project Overview

Built an end-to-end data analytics and sentiment intelligence system to analyze Amazon product reviews, uncover customer sentiment patterns, and evaluate product performance using structured SQL storage and Python-based analytics.

The project combines **data cleaning, SQL integration, sentiment analysis, and visualization** to support data-driven product insights.

## Problem Statement

Amazon product reviews contain valuable customer feedback, but raw review data is:

- Unstructured and noisy
- Difficult to analyze at scale
- Hard to convert into actionable insights

The goal was to transform raw review data into **structured insights** that reveal:

- Overall customer sentiment
- Product performance trends
- Rating vs sentiment alignment

## Solution Overview

I designed a complete analytics pipeline that:

- Processes raw Amazon review data
- Stores structured data in **Azure SQL**
- Performs **sentiment analysis** on customer reviews
- Visualizes performance trends for decision-making

### Key Steps

- Cleaned and preprocessed review text and metadata
- Connected Python to Azure SQL database
- Loaded structured review data into SQL tables
- Applied sentiment polarity analysis to reviews
- Analyzed rating distribution and sentiment trends
- Visualized insights using charts and graphs

## Data Pipeline & Architecture

**Flow:**

Raw CSV Reviews → Python Data Cleaning → Azure SQL Storage → Sentiment Analysis → Visualization & Insights

This structure ensures scalability and separation between storage and analysis.

## Tools & Technologies

- **Python:** Core data processing and analysis
- **Azure SQL Database:** Structured cloud storage
- **Pandas & NumPy:** Data manipulation
- **Matplotlib & Seaborn:** Data visualization
- **NLP Techniques:** Sentiment polarity analysis
- **Jupyter Notebook:** Development & documentation

## Performance & Results

This project focused on **analytical performance and insight generation**, not model training.

### Key Outcomes

- Processed and analyzed **thousands of Amazon product reviews**
- Classified reviews into **positive, neutral, and negative sentiment**
- Identified a correlation between **star ratings and sentiment polarity**
- Highlighted products with high ratings but negative sentiment patterns
- Enabled SQL-based querying for faster insight retrieval

### Example Insights

- High-rated products sometimes contained clusters of negative sentiment
- Sentiment polarity provided a deeper understanding than star ratings alone
- SQL storage significantly improved structured querying and analysis speed

## Visual Evidence

Include the following from your notebook:

- Sentiment polarity visualizations

<img width="588" height="448" alt="Screenshot 2026-01-15 094256" src="https://github.com/user-attachments/assets/945c5fcc-5165-4153-94ae-2f5413521d6d" />


- Logistic Regression - Confusion Matrix

<img width="593" height="463" alt="Screenshot 2026-01-15 094414" src="https://github.com/user-attachments/assets/df3b25ea-2d5d-4505-b414-065c7bf3beba" />


- Word Clouds for all Positive, Negative and Neutral Sentiments

<img width="802" height="497" alt="Screenshot 2026-01-15 094553" src="https://github.com/user-attachments/assets/157762b1-532b-4c0a-9ce6-b0dd2a16303e" />


## Dashboard:

**Link:** [https://github.com/Nishigandha-Wankhade/Sentiment-and-Customer-Voice-Analysis-for-Amazon-Product-Reviews/blob/main/Sentiment and Customer Voice Analysis for Amazon Product Reviews.png](https://github.com/Nishigandha-Wankhade/Sentiment-and-Customer-Voice-Analysis-for-Amazon-Product-Reviews/blob/main/Sentiment%20and%20Customer%20Voice%20Analysis%20for%20Amazon%20Product%20Reviews.png)

<img width="1429" height="804" alt="Screenshot 2026-01-15 095256" src="https://github.com/user-attachments/assets/7a5555c8-6ac6-4c64-aeb5-06d6093b7d34" />


## Key Learnings

- Practical integration of **Python with Azure SQL**
- Importance of sentiment analysis beyond numeric ratings
- Designing scalable analytics pipelines
- Translating raw text data into business insights

## Future Improvements

- Use advanced NLP models like VADER or BERT
- Add real-time review ingestion
- Build a dashboard using Power BI or Streamlit
- Automate sentiment scoring for new reviews

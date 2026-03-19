# 📊 Employee Sentiment & Attrition Risk Intelligence Dashboard

## 🚀 Overview
This project is an end-to-end analytics solution that combines Natural Language Processing (NLP), data engineering, and business intelligence to analyze employee feedback and identify attrition risk patterns.

Using 10,000+ Glassdoor reviews, the system transforms unstructured text data into actionable insights through sentiment analysis, risk scoring, and interactive Power BI dashboards.

---

## 🎯 Objectives
- Analyze employee sentiment using NLP techniques
- Identify high-risk employees likely to leave
- Track trends in employee satisfaction over time
- Detect key drivers of dissatisfaction (management, compensation, culture)
- Enable HR teams to make data-driven retention decisions

---

## 🧠 Key Features
- 🔍 Sentiment Analysis using VADER NLP on employee reviews
- ⚠️ Attrition Risk Scoring using multiple behavioral signals
- 🧹 Data Cleaning & Feature Engineering (Python, Pandas)
- 📊 Interactive Power BI Dashboard (4 pages)
- 🧱 Data Modeling with star schema
- 📈 Time-based trend analysis using DAX

---

## 📊 Dashboard Pages
1. **Company Health Overview**
   - Avg Rating, Sentiment Score, High Risk %
   - Trend analysis over time

2. **Role & Department Analysis**
   - Satisfaction and risk across roles
   - Sub-rating comparisons

3. **Complaint & Topic Analysis**
   - Top complaint categories
   - Word cloud of employee feedback

4. **Risk Intelligence Dashboard**
   - High-risk employee segments
   - Risk trends and critical reviews

---

## 🤖 Machine Learning / NLP
- Applied **VADER Sentiment Analysis** on text reviews
- Generated sentiment scores for Pros and Cons
- Classified reviews into Positive, Neutral, Negative
- Extracted keywords and complaint topics using NLP techniques

---

## ⚠️ Attrition Risk Model
A composite risk scoring system was developed using:

- Low rating (≤ 2)
- Negative sentiment
- Presence of toxic keywords
- Negative recommendation
- CEO disapproval

📌 Reviews are categorized into:
- Low Risk
- Medium Risk
- High Risk
- Critical Risk

---

## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy, NLTK, VADER)**
- **Power BI**
- **DAX**
- **Power Query**
- **Data Modeling (Star Schema)**

---

## 📂 Dataset
- **Source:** Glassdoor Reviews Dataset  
- **Size:** 10,000+ records, 23 columns  
- **Type:** Structured + Unstructured (text)

---

## 📈 Key Insights
- High discounts in compensation-related feedback drive negative sentiment
- 30%+ employees fall under medium to high attrition risk
- Management and work-life balance are top complaint areas
- Former employees show significantly lower satisfaction scores

---


## ▶️ How to Run
1. Run Python notebook for data preprocessing & NLP  
2. Export cleaned dataset  
3. Load dataset into Power BI  
4. Use dashboard to explore insights  

---

## 💡 Key Learnings
- Applied NLP techniques on real-world text data  
- Built a risk scoring system using multiple features  
- Designed interactive dashboards for business insights  
- Combined ML + Analytics + BI in one pipeline  

---

## 👤 Author
**Ansh Khajuria**

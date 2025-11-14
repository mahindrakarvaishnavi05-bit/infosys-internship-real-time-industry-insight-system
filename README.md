# Real-Time Industry Insight & Strategic Intelligence System

A data-driven intelligence platform that gathers, processes, analyzes, and visualizes real-time industry information from open public sources. This project enables organizations to monitor market dynamics, competitor performance, financial trends, and public sentiment to support strategic decision-making.

---

## 🚀 Features

- 🔍 **Real-time Industry Data Collection**
  - Extracts data from trusted public sources (Wikipedia, stock market portals, news sites, social platforms, etc.)

- 📦 **Data Cleaning & Preprocessing**
  - Handles missing values, formatting issues, duplicate entries, and inconsistencies.

- 📊 **Data Visualization**
  - Generates meaningful visual insights through charts and trend analysis.

- 🧠 **Sentiment & Pattern Insights**
  - Detects public sentiment on technology, companies, or sectors (Sprint-2 ready).

- 🧾 **Structured Data Storage**
  - Organized datasets ready for further ML/BI systems.

- 📑 **Report Generation**
  - Capable of producing industry insight summaries.

---

## 🧠 Objective

To provide companies, analysts, investors, and researchers a centralized platform that offers:
- Competitor analysis
- Market trends
- Growth rate observations
- Strategic business intelligence
- Better-informed decision making

---

## 📂 Sprint-1 Deliverables (Milestone Achieved ✅)

1. ✅ Data sourcing from external internet sources  
2. ✅ Data extraction & formatting  
3. ✅ Handling missing/incomplete values  
4. ✅ Dataset structuring and cleaning  
5. ✅ Exploratory analysis & observations  
6. ✅ Initial visualizations  
7. ✅ Final processed dataset export  

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|---------|-------------------|
| Programming | Python |
| Notebook Environment | Google Colab |
| Data Handling | Pandas |
| Data Fetching | Requests |
| Web Scraping | BeautifulSoup |
| Visualization | Matplotlib |

---
2️⃣ Install Dependencies
pip install pandas requests beautifulsoup4 matplotlib

3️⃣ Open Google Colab
Upload and run the notebook.


📌 Usage Workflow

1.Enter target industry/company keyword<br>
2.Run data scraping cells<br>
3.Automatically clean & normalize incoming data<br>
4.Generate visual insights<br>
5.Export processed dataset for reporting or ML pipelines<br>


📊 Example Insights Generated (Sprint-1)

Market capitalization trends<br>
Company background details<br>
Industry growth indicators<br>
Recent news mentions<br>
Comparison tables<br>
Line/bar trend charts<br>


📝 Observations & Findings

Some sources restrict live scraping (handled via fallback logic)<br>
Data formats vary heavily across platforms<br>
Cleaning pipeline improves quality significantly<br>
Trend visualization reveals growth potential<br>



# 📊 Sprint 2 – Advanced Intelligence & Visualizatio
## ⭐ 1. Executive Summary

In Sprint 2, the project moved from basic data processing to **advanced AI-based analysis and better visual results**.
We focused on three main modules:
  
  Module 1: Analysis Engine
  Module 2: Trend Forecasting
  Module 3: Alert System

All goals for these modules were completed.

### Key Achievements

 Replaced simple TextBlob sentiment analysis with Gemini API, which gives more accurate and structured sentiment results.
 Set up historical price data using yfinance to prepare for future prediction models.
 Built a Slack Alert System that sends alerts when sentiment drops or price changes a lot.
 Created an interactive dashboard with price trend, LLM sentiment, and summaries.

## ✅ 2. Milestone Fulfillment & Status

| Milestone (Planned)              | Work Completed (Infosys_Project.ipynb)                                               | Status |
| -------------------------------- | ------------------------------------------------------------------------------------ | ---------- |
| Replace basic sentiment with LLM | Gemini API integrated using Function Calling for structured sentiment and summaries  | ✔ Complete |
| Start trend forecasting setup    | Collected updated price data using yfinance for upcoming models (ARIMA/LSTM/Prophet) | ✔ Complete |
| Design alert system              | Created and tested Slack alert function and alert triggers                           | ✔ Complete |
| Create strategic dashboard       | Combined all results into one interactive dashboard using Plotly                     | ✔ Complete |

## 🎯 3. Conclusion

Sprint 2 showed that the system can now:

 Pull and update data
 Analyze sentiment using a strong LLM
 Send alerts automatically
 Display everything clearly in a dashboard

Contributors
<br>
 Anshika Gupta <br>
 Gopichand    <br>
 Janmejay Singh <br>
 Vaishnavi Mahindrakar      <br>
 



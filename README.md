# SpaceX Falcon 9 First Stage Landing Prediction
### IBM Data Science Professional Capstone Project

**GitHub Repository:** [github.com/eunicewellis/IBM-SpaceX-Capstone-1](https://github.com/eunicewellis/IBM-SpaceX-Capstone-1)

---

## 🚀 Project Overview
SpaceX advertises Falcon 9 rocket launches at **$62 million**, compared to traditional providers charging upward of **$165 million** per launch[cite: 1]. The principal driver of these cost savings is the successful recovery and reuse of the Falcon 9 first stage booster. 

The objective of this project is to build an end-to-end data science pipeline to predict whether the Falcon 9 first stage will land successfully on a ground pad or autonomous spaceport drone ship (ASDS), enabling commercial competitors to optimize bidding strategies and operational risk assessment[cite: 1].

---

## 📊 Key Findings & Metrics
* **Overall Landing Success Rate:** 66.7%[cite: 1]
* **Top Launch Site:** KSC LC-39A (**76.9%** success rate)[cite: 1]
* **Top Orbits:** ES-L1, GEO, HEO, and SSO achieved **100%** successful recovery[cite: 1]
* **Optimal Payload Range:** Payloads between **2,000 kg and 5,300 kg** yield the highest landing success rate[cite: 1]
* **Best Machine Learning Model:** Decision Tree Classifier (max depth = 4) achieving **83.33%** test accuracy[cite: 1]

---

## 🗂️ Repository Structure
* `notebooks/`: Contains all Jupyter notebooks for Data Collection (API & Web Scraping), Data Wrangling, EDA (Matplotlib/Seaborn & SQL), Geospatial Analysis (Folium), and Machine Learning.
* `dash_app/`: Contains `spacex_dash_app.py` for the interactive Plotly Dash web dashboard.
* `reports/`: Contains the comprehensive final capstone PDF report.

---

## 🛠️ Methodology & Tech Stack
* **Data Extraction:** SpaceX REST API v4 & BeautifulSoup4 Web Scraping[cite: 1].
* **Data Wrangling:** Pandas, NumPy, One-Hot Encoding (72 binary features), and mean imputation[cite: 1].
* **Visual Analytics:** Seaborn, Matplotlib, SQLite query analytics, Folium geospatial interactive maps, and Plotly Dash[cite: 1].
* **Machine Learning:** Scikit-Learn (`GridSearchCV` tuning across Logistic Regression, SVM, Decision Tree, and KNN)[cite: 1].
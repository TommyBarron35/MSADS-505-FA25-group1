# Flight ETA & SLA Risk Prediction

## 📖 Project Overview
This project applies **machine learning models** to predict flight Estimated Time of Arrival (ETA) and assess **Service Level Agreement (SLA) risk**, with a focus on supply chain efficiency.  
Delays in air transport can propagate downstream, causing missed connections, inventory shortages, and cost overruns. Our solution combines predictive modeling, interpretability methods, and actionable insights to optimize operational decisions.

---

## 🎯 Problem Statement
**How can machine learning models be applied to predict flight ETAs and SLA risks in order to optimize operational decisions for supply chain efficiency?**

Objectives:
1. Predict flight arrival delays (minutes).
2. Classify flights into *on-time* vs. *late* categories.
3. Provide actionable recommendations by identifying operational levers (e.g., carrier choice, seasonality, airport effects).

---

## 📊 Datasets
- **Primary:** [U.S. DOT On-Time Performance Data (1995–2025)](https://www.transtats.bts.gov/ONTIME/) :contentReference[oaicite:10]{index=10}  
- **Supplementary:** [Brazilian Olist E-commerce Dataset (Kaggle)](https://www.kaggle.com/olistbr/brazilian-ecommerce) :contentReference[oaicite:11]{index=11}  

---

## 🔧 Methodology
1. **Data Acquisition & Preparation**
   - Download BTS data for major airports.
   - Merge flights, carriers, weather, airport metadata.
   - Feature engineering (seasonality, carrier averages, hubs).
2. **Exploratory Data Analysis**
   - Visualize delays by season, carrier, and weather.
3. **Modeling**
   - Regression (LightGBM/XGBoost) for ETA.
   - Classification (LogReg, k-NN, RF) for SLA risk.
   - Evaluation: RMSE, MAE, Precision/Recall, F1, ROC-AUC.
4. **Interpretability**
   - SHAP values to quantify operational levers.
5. **Deliverables**
   - ETA Predictor
   - SLA Risk Classifier
   - Dashboard prototype
   - Cost-impact report

---

## 📅 Timeline
- **Week 1–2:** Data acquisition & cleaning ✅  
- **Week 3:** Exploratory Data Analysis (in progress)  
- **Week 4–5:** Model development  
- **Week 6:** Evaluation + SHAP analysis  
- **Week 7:** Dashboard design + recommendations  
- **Week 8:** Final report + presentation prep:contentReference[oaicite:12]{index=12}

---

## 📂 Deliverables
- 📑 Business Brief (PDF)  
- 📊 Executive Summary Slides (≤6 slides)  
- 📝 Technical Notebook (Jupyter + PDF)  
- 🎥 Video Presentation (15–20 min)  
- 💻 GitHub Repository with all code and documentation:contentReference[oaicite:13]{index=13}

---

## 🔗 References
- Bureau of Transportation Statistics. (2025). *Airline On-Time Performance Data*. U.S. Department of Transportation. [https://www.transtats.bts.gov/ONTIME/](https://www.transtats.bts.gov/ONTIME/)  
- Kaggle. (2018). *Brazilian E-commerce Public Dataset by Olist*. [https://www.kaggle.com/olistbr/brazilian-ecommerce](https://www.kaggle.com/olistbr/brazilian-ecommerce)  
- PEP 8: [Python Style Guide](https://pep8.org/) :contentReference[oaicite:14]{index=14}  
- Streamlit Intro: [YouTube](https://www.youtube.com/watch?v=xl0N7tHiwlw)  
- Dash Tutorial: [YouTube](https://www.youtube.com/watch?v=7m0Bq1EGPPg)  
- MS-ADS Resources: [GitHub Resources Page](https://usd-msads.github.io/resources/) :contentReference[oaicite:15]{index=15}

---

## 👥 Team Contributions
- **Darren Chen** – Project lead, modeling, GitHub repo  
- **[Teammate 1]** – Data acquisition & cleaning  
- **[Teammate 2]** – Dashboard & business brief  
*(To be updated with specific contributions in final report)*

---

## 📌 Notes
- Follow course requirements for deliverables (see [Final Team Project Introduction PDF](https://sandiego.instructure.com/courses/23304/files/3356078?wrap=1)) :contentReference[oaicite:16]{index=16}  
- No extensions will be granted for final submission.  

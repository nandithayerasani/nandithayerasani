<h1 align="center">Nanditha Yerasani</h1>
<p align="center"><b>Data Analyst | QA Engineer turned Data Scientist</b></p>

<p align="center">
  <a href="https://linkedin.com/in/nanditha-yerasani"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:nyerasani@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Open_to-Data_Analyst_Roles-2ea44f?style=for-the-badge" />
</p>

---

### 👋 About Me

I'm a data professional with a QA engineer's instinct for what breaks — and I use that instinct to catch the mistakes that make models and dashboards *look* right when they aren't.

- 🎓 **M.S. in Data Science**, University of Texas at Arlington (May 2026)
- 📊 My work spans EDA, model development, and turning findings into stakeholder-ready visuals with **Python, MS SQL, and Power BI**
- 🕵️ My edge: a QA background means I default to *distrusting* a clean result until I've checked the split, the leakage, and the assumptions behind it
- 📌 Currently seeking **Data Analyst** roles (Business Analyst / SDET also welcome)

---

### 🚀 Featured Projects

**📦 Retail Demand Forecasting** — *LightGBM, XGBoost, SHAP, Streamlit*
> **Problem:** Forecast weekly demand across 10 stores × 25 products to reduce stockouts and overstock.
- Engineered lag, rolling-window, EWM, and cyclical features on 26,250 weekly observations; selected LightGBM as the final model (MAPE 14.88%, MAE 9.76)
- Caught an AI coding assistant using a random train/test split on time-series data — a silent leak through lag features — and rebuilt the pipeline with a time-based split
- Added SHAP explainability and stockout risk detection, delivered as an interactive multipage Streamlit forecasting application

**🎓 StudyBridge — Peer Tutoring Platform** — *React, Node.js, MySQL, Postman, OpenAI API*
> **Problem:** In a platform handling bookings, messaging, and payments, a silent bug can cost a student real money or a missed session.
- Designed the MySQL database schema and the UI, then led QA across the full stack: requirement analysis, UI, API (Postman), database, and performance testing
- Validated data integrity by querying MySQL after every booking, messaging, and payment action, confirming that what the UI displayed matched what was actually stored
- Tested the OpenAI-powered features for non-deterministic LLM output, where the same input can return different responses and exact-match assertions break

**✈️ Flight Delay Prediction** — *Random Forest, LSTM*
> **Problem:** Predict flight delays from 180K U.S. domestic flight records (BTS, 2017–2018) enriched with hourly weather data.
- Tuned a Random Forest with RandomizedSearchCV, encoding airports as lat/long coordinates instead of high-cardinality one-hot features
- Built an LSTM on weather and time sequences to compare a sequential model against a tabular one
- On review, traced Random Forest's 97% accuracy to leakage (departure delay used to predict arrival delay) and found the LSTM had collapsed to the majority class

**🛰️ River Stream Identification via Satellite Imagery** — *SVM, Random Forest, U-Net, ResNet*
> **Problem:** Manually mapping river networks from satellite imagery is slow, which limits water resource management at scale.
- Compared classical ML (SVM, Random Forest) against deep learning segmentation (U-Net, ResNet) for detecting river networks
- Evaluated where pixel-level segmentation outperformed classical classifiers on this imagery

---

### 🛠️ Tech Stack

<p> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <br/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" /> <img src="https://img.shields.io/badge/XGBoost-black?style=flat-square" /> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <br/> <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" /> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" /> <br/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" /> <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" /> <br/> <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" /> <img src="https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white" /> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" /> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white" /> </p>

---

### 🌿 Outside Work

I keep two Instagram pages going — one for **[perfumery](https://instagram.com/sure.sometimes)**, where I dig into how scent notes are chemically constructed, and one for **[travel photography](https://instagram.com/nandithareddyy)**, where I document the same "notice the pattern others miss" instinct through a camera instead of a dataset.

---

<p align="center"><i>Thanks for stopping by — always happy to talk Data, QA, or the overlap between the two.</i></p>

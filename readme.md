
# 🚀 Applied Data Science Capstone


## 📄 Project Overview
This project is part of the **IBM Data Science Professional Certificate** capstone, focusing on predicting whether the first stage of SpaceX's Falcon 9 rocket will land successfully. Reusability is key to SpaceX's cost efficiency—while competitors charge over **$165 million per launch**, SpaceX offers launches at **$62 million**, largely due to first-stage recovery.

By analyzing historical launch data and applying **machine learning classification models**, we determine the likelihood of a successful landing, which helps estimate launch costs for competitive bidding.

---

## 🔍 Key Questions
1. **How do payload mass, launch site, and orbit type affect landing success?**  
2. **Has landing success improved over time?**  
3. **Which machine learning model best predicts first-stage landing outcomes?**

---

## 📊 Methodology

### 1️⃣ Data Collection
- **SpaceX API** – Fetched historical launch data
- **Web Scraping** – Extracted additional details from Wikipedia

### 2️⃣ Data Wrangling & EDA
- **Cleaned & filtered** data (handled missing values, outliers)
- **One-Hot Encoding** for categorical features (e.g., launch site, orbit type)
- **Exploratory Data Analysis (EDA)** with visualizations (Matplotlib, Plotly, Folium)

### 3️⃣ Predictive Modeling
Trained and evaluated **four classification models**:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- k-Nearest Neighbors (KNN)

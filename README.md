# Hi, I'm Shawn Duong 

**BS Machine Learning — UC San Diego (June 2026)**  
Seeking **Data Analyst & Data Scientist roles** in Orange County, CA

---

## About Me

I'm a Machine Learning graduate from UC San Diego with hands-on experience building data pipelines, statistical models, and classification systems. I'm passionate about applying data science to solve real-world problems in sports analytics, government, and technology.

Currently building a portfolio of end-to-end data science projects and actively seeking entry-level Data Analyst, Data Science, or Machine learning Roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-shawnduong-blue?style=flat&logo=linkedin)](https://linkedin.com/in/shawn-duong18)
[![Email](https://img.shields.io/badge/Email-shawnduong18%40gmail.com-red?style=flat&logo=gmail)](mailto:shawnduong18@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-green?style=flat&logo=adobe)](https://drive.google.com/file/d/137NhtpN6QUE_V_g5lzXAQ1IEsCqiy_dl/view)

---

## Skills

**Languages**  
Python · SQL · R 

**Data & ML Libraries**  
Pandas · NumPy · Scikit-learn · Statsmodels · PyTorch · TensorFlow

**Visualization & Tools**  
Tableau · Matplotlib · Seaborn · Excel · Git/GitHub · VS Code

**Methodologies**  
Machine Learning (Classification, Regression, Clustering) · Statistical Modeling · Hypothesis Testing · ETL · Cross-Validation · Feature Engineering · EDA · Data Visualization

---

## Projects

### 1. **UCSD Campus Parking Occupancy Prediction Dashboard**
Deployed a production system predicting parking availability across 43 campus lots serving 10,000+ daily users.

**Impact:** Reduced parking search time by enabling real-time lot predictions and geospatial ranking.

**Technical Work:**
- Built **ETL pipeline** consolidating 20 quarterly Excel files (2019-2026, 3 different schemas) into 26,000+ observations using Pandas
- Engineered 12+ temporal and spatial features (hour of day, day of week, seasonality, geospatial distance)
- Trained 4 classification models (Logistic Regression, Random Forest, KNN, XGBoost) with 5-fold stratified cross-validation
- Achieved **73.1% accuracy** with XGBoost (5.8-point improvement over baseline)
- Deployed interactive dashboard to production (GitHub Pages + Leaflet.js + Chart.js)
- Integrated OpenStreetMap Overpass API with intelligent caching for 10,000+ monthly users

**Tools:** Python, Pandas, Scikit-learn, SQLite, Leaflet.js, Chart.js  
**[View on GitHub](https://github.com/shawnduong18/ucsd-parking-dashboard)** | [Live Dashboard](https://shawnduong18.github.io/ucsd-parking-dashboard/)

---

### 2. **Gamma-Ray Classification: Logistic Regression vs. Support Vector Machines**
Rigorous comparison of two linear classifiers on the MAGIC Gamma Telescope dataset (19,020 observations, 10 features).

**Key Finding:** Both models plateau at ~79% accuracy due to linear decision boundary limitations, not classifier choice.

**Technical Work:**
- Implemented **5-fold stratified cross-validation** with L2 regularization parameter sweep (λ: 0.1-10)
- Evaluated with comprehensive metrics: accuracy, sensitivity, specificity, precision, F1, AUC-ROC
- Plotted train/test accuracy to assess overfitting (minimal gap → model stability with 15K training points/fold)
- Extracted feature importance (fLength and fAlpha are primary drivers)
- Visualized class distributions to validate hypothesis: multivariate classification is necessary

**Tools:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn  
**[View on GitHub](https://github.com/shawnduong18/gamma-ray-classification)**

---

### 3. **NBA Win Rate Prediction with Statistical Analysis**
Analyzed 10 seasons of NBA data to determine which factors (offense vs. defense) drive winning.

**Key Finding:** Defensive rating (R² = 0.501) is a stronger predictor of wins than offensive rating (R² = 0.486).

**Technical Work:**
- Extracted, cleaned, and transformed raw NBA web data using Pandas
- Engineered offensive and defensive features from raw stats
- Built multiple regression models using Statsmodels with cross-validation
- Performed statistical significance testing (p < 0.05) to validate findings
- Translated insights into actionable roster-building recommendations
- Visualized results with Matplotlib and Seaborn

**Tools:** Python, Pandas, Statsmodels, Matplotlib, Seaborn  
**[View on GitHub](https://github.com/shawnduong18/COGS-108-Final)**

---

## 💼 Experience

**Undergraduate Data Researcher** — UC San Diego  
*Mar 2026 – June 2026 | 10 hours/week*
- Deployed production dashboard serving 10,000+ monthly users with real-time predictions
- Built ETL pipeline consolidating 20+ Excel files (26,000+ observations)
- Trained and evaluated 4 ML models achieving 73.1% accuracy (5.8-point gain over baseline)
- Integrated external APIs (OpenStreetMap) with production caching

**ITS Service Desk Technician** — UC San Diego  
*Sept 2025 – June 2026 | 20 hours/week*
- Supported 30,000+ UCSD affiliates with 60% first-contact resolution rate
- Logged and analyzed incident data in ServiceNow to identify technical trends
- Escalated critical network outages to infrastructure teams

---

## What I'm Looking For

**Ideal Role:**
- Entry-level Data Analyst or Data Scientist
- Location: Orange County, CA (or remote)
- Focus: SQL, Python/R, data analysis, visualization, statistical modeling
- Industry: Open to sports, government, technology, healthcare

**Interested in:**
- Federal government analytics
- Sports analytics (MLB, NBA organizations)
- Data-driven business analytics

---




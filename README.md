# Sebastian Bangemann - Data-Analytics-Portfolio

Hi, I’m Sebastian! I’m passionate about turning complex data into clear, actionable insights that help businesses thrive. With a background in data analysis, I specialize in leveraging tools like SQL, Python, Excel, and Tableau/Power BI to uncover hidden trends and opportunities that drive growth.

I thrive on problem-solving, whether working solo or collaborating with teams, always focusing on delivering impactful solutions that make a real difference. On this GitHub, you’ll find a selection of my most exciting projects where I explore the power of data to create value. Let’s connect and see what we can build together! 

---

## 👨‍💻 **About Me**  

🎓 As a data analyst, I blend my technical expertise with a genuine passion for leveraging data to address real-world challenges. I have hands-on experience in data cleaning, transformation, and visualization, and I’m always eager to collaborate on new projects to grow and refine my skills.

Outside of work, I love exploring side projects that involve uncovering hidden patterns and creating dashboards that simplify data for others. I thrive on tackling complex problems and am always excited to share insights that drive smarter business decisions.  

---

## 🗂️ **Table of Contents**  

- [About Me](#about-me)  
- [Portfolio Projects](#portfolio-projects)  
  - [🦄 1. Unicorn Company: Data Exploration & Insights (SQL + Tableau + Google Sheets)](https://github.com/seb-bange/unicorn_project)
  - [🚗 2. Car Data Analysis (Python)](https://github.com/seb-bange/car_project_python)
  - [🚗 3. Vehicle Classification Model for Prospect Auto (Supervised ML)](https://github.com/seb-bange/ml_supervised_car)
  - [🚗 4. Vehicle Classification Model for Prospect Auto (Unsupervised ML)](https://github.com/seb-bange/ml_unsupervised_car)  
- [Education](#education)
- [Certificates](#certificates)  
- [Contact](#contact)  

---

## 📊 **Portfolio Projects**

### **🦄 1. Unicorn Company: Data Exploration & Insights (SQL + Tableau + Google Sheets)

**Objective:** Conduct comprehensive data exploration using SQL and create an executive-level Tableau dashboard to deliver insights and business recommendations.

**Project Overview:**
This project involved analyzing Unicorn Company’s sales, profit, and customer data using SQL queries, then translating the findings into an actionable Tableau dashboard. The focus was on identifying high-performing regions, products, and customer segments.

**Part 1: Data Exploration with SQL**
	•	Performed in-depth exploration of the Unicorn database to answer key business questions regarding sales, profits, and customer behavior.
	•	Cleaned and merged tables, performed aggregations, and ranked cities, products, and regions based on performance.

**Part 2: Analysis with Google Sheets**
	•	Utilized pivot tables and created calculated columns (e.g., price per unit).
	•	Highlighted underperforming regions through conditional formatting.

**Part 3: Insights & Dashboard with Tableau**
	•	Built a Tableau dashboard to present key insights, trends, and actionable recommendations to support data-driven business decisions.

**Skills:**
	•	SQL: Data querying, joins, DML/DQL operations, subqueries
	•	Data cleaning and filtering
	•	Tableau: Data visualization and dashboard creation
	•	Business insights and recommendations

**Technologies:** PostgreSQL, Tableau

**Key Insights:**
	•	Identified the most profitable cities, customer segments, and products across regions.
	•	Pinpointed areas of growth opportunity in the East and South regions.
	•	Suggested changes in discount strategies to enhance profit margins.

**📈 Results:**
	•	Tableau Public Dashboard
	•	SQL Queries

---

### **🚗 2. Car Market Analysis (Python)**

**Objective**: Clean, transform, and analyze car specification and pricing data to identify market trends and key relationships.

**Overview:**
This project leveraged Python for data preprocessing, feature engineering, and exploratory analysis of a car dataset. The dataset included details such as make, model, engine specifications, fuel types, and pricing.

**Key Steps:**
- Processed and cleaned data by handling missing values, standardizing formats, and filtering for cars from 1995 onward.
- Engineered new features like **Total MPG** and **Price per Horsepower** to enhance analytical depth.
- Performed exploratory data analysis (EDA) to uncover pricing trends, horsepower distributions, and market segmentation.

**Skills Applied:**
- Data preprocessing and transformation (Pandas, NumPy)
- Exploratory analysis and statistical insights
- Correlation analysis
- Data visualization (Matplotlib, Seaborn)

**Tools & Technologies:** Python (Pandas, NumPy, Matplotlib, Seaborn)

**Key Findings:**
- Identified a strong correlation between engine horsepower and car prices.
- Found that larger vehicles and premium models tend to have significantly higher prices.
- Analyzed efficiency trends across different transmission types.

**📈 Project Deliverable:**
- [Jupyter Notebook](https://colab.research.google.com/drive/1SGQndKAqy39gFsRqBYRbmIkh7FxZD_MG?usp=sharing) 

---

### **🚗 3. Vehicle Classification Model for Prospect Auto (Supervised ML)**

**Objective:**
Develop a machine learning model to classify vehicles based on silhouette features, supporting Prospect Auto’s internal tools.

**🔍 Overview:**

This project uses supervised machine learning to predict vehicle class from silhouette data. After cleaning and exploring the dataset, several models were tested to find the most accurate and generalizable classifier.

**🛠️ Steps:**
- Data preprocessing and normalization
- Exploratory Data Analysis (EDA)
- Model training:
	- Logistic Regression
	- KNN
	- SVM (Linear, Polynomial, RBF)
	- Decision Tree
	- Random Forest
	- Gradient Boosting
	- Evaluation using Accuracy, Precision, Recall, F1-Score, ROC AUC
	- Visualization of performance (heatmap, line plot)

**✅ Key Result:**

SVM with RBF kernel achieved >99% in all metrics with excellent generalization and is recommended for deployment.

**📦 Technologies:**

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn

**📈 Deliverable:**
- Final model recommendation
- Evaluation plots
- Clean and reproducible Jupyter Notebook

**📓 Notebook:**

👉 - [Jupyter Notebook](https://colab.research.google.com/drive/1SGQndKAqy39gFsRqBYRbmIkh7FxZD_MG?usp=sharing)

---

### **🚗 4. Vehicle Silhouette Clustering – Prospect Auto**

📄 **Project Overview:**

This project focuses on clustering a dataset of vehicle silhouettes based on geometric features extracted from the silhouettes of vehicles in various angles. The dataset includes three vehicle types: bus, van, and car. The goal is to explore unsupervised learning techniques to classify these vehicles based on their silhouette features.

🧠 **Problem Statement:**

Prospect Auto requested a model to differentiate between three vehicle types based on their silhouettes. The task is to classify vehicles without labeled data using clustering algorithms.

🛠 **Project Steps:**
- Data Preparation
- Imported necessary libraries
- Loaded and read the dataset
- Normalized and standardized features
- Dimensionality Reduction
- Applied PCA to reduce the 18 features while preserving data variance
- Clustering Models
- Applied K-Means Clustering
- Applied DBSCAN Clustering
- Evaluation
- Measured clustering performance using Silhouette Score and other relevant metrics

📊 **Evaluation & Results**
- **K-Means:**
	- Silhouette Score: 0.31
	- **Conclusion:** K-Means showed significant overlap between clusters, making it unsuitable for this dataset.
- **DBSCAN:**
  	- Silhouette Score: 0.27
	- Noise Points: 155 (≈ 20% of the data)
	- Davies-Bouldin Index: ≈ 1.0
	- **Conclusion:** DBSCAN also underperformed due to high noise and poor cluster separation.

✅ **Conclusion:**

Supervised learning, particularly using SVM with an RBF kernel, yielded exceptional results. However, unsupervised clustering algorithms like K-Means and DBSCAN struggled with the dataset.

🔎 **Recommendation:** Supervised learning (SVM with RBF kernel) remains the optimal approach for this problem.

📓 **Notebook:**

[Unsupervised ML Notebook](https://colab.research.google.com/drive/1YW85WScqkZJg2i3ze1pLU2Sy97kBA9bl?usp=sharing)


## 🎓 **Education**  
- **Data Analytics at Masterschool (in Progress)**
- **MBA at ENEB - Escuela de Negocios Europea de Barcelona (in Progress)**
- **Master in Big Data and Business Intelligence at ENEB - Escuela de Negocios Europea de Barcelona (in Progress)**


---

## 📜 **Certificates**  
- [Google Data Analytics](https://coursera.org/share/cfb202ea7cfeff30aa83acff4a1d5d91)
---

## 📬 **Contact**  
Let's connect! Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/sebastian-bangemann/) or email to discuss projects, collaborations, or opportunities.  

---  

I hope you find this project portfolio inspiring! 🌟


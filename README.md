# 📊 Learning Analytics – Big Data Analysis with PySpark

## 🧠 Project Overview
This project focuses on the analysis of a large-scale real-world dataset using **Big Data technologies** and **Machine Learning techniques**, as part of the *Learning Analytics* course (Master TIA – Year 2).

The main goal is to demonstrate the full Big Data pipeline:
- data extraction from a cloud platform,
- distributed data processing,
- exploratory data analysis,
- and predictive modeling using PySpark.

The project uses the **Chicago Taxi Trips** public dataset, available through **Google Cloud BigQuery**.

---

## 📂 Dataset
- **Source:** Google Cloud Platform – BigQuery Public Datasets  
- **Dataset:** Chicago Taxi Trips  
- **Original size:** ~15 GB  
- **Working subset:** ~500,000 records  

The subset was extracted using SQL queries in BigQuery and processed in a distributed manner using PySpark.

---

## 🛠️ Technologies Used
- **Google Cloud Platform (BigQuery)** – data source  
- **Google Colab** – cloud execution environment  
- **PySpark (Apache Spark)** – distributed data processing  
- **Spark MLlib** – machine learning algorithms  
- **Python** – analysis and visualization  

---

## 🔄 Data Processing Pipeline
1. Data extraction from BigQuery  
2. Loading data into PySpark  
3. Data cleaning and preprocessing  
4. Exploratory Data Analysis (EDA)  
5. Feature engineering  
6. Machine Learning model training  
7. Model evaluation and comparison  

---

## 📊 Exploratory Data Analysis
The exploratory analysis includes:
- Descriptive statistics
- Histograms for numerical variables
- Scatter plot analysis
- Correlation matrix and heatmap

These steps provide insights into data distribution, outliers, and relationships between variables.

---

## 🤖 Machine Learning Models
The following regression models were implemented using **PySpark MLlib**:

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosted Trees Regressor**

### 🎯 Target Variable
- `trip_total` – total cost of a taxi trip

### 📈 Evaluation Metrics
- **RMSE (Root Mean Squared Error)**
- **R² (Coefficient of Determination)**

A comparative analysis highlights the superior performance of tree-based models for capturing non-linear relationships.

---

## 📑 Project Structure
├── LA_BigData_ChicagoTaxi_PySpark.ipynb
└── README.md


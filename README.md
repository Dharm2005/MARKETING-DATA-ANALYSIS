# 📊 Marketing Customer Data Analysis (EDA)

## 📘 Overview
This project performs an **in-depth Exploratory Data Analysis (EDA)** on a **marketing customer dataset** to understand customer demographics, spending behavior, purchase patterns, and campaign responses.

The primary goal of this analysis is to **extract actionable business insights** that can help improve **customer segmentation, marketing strategy, and campaign effectiveness**.

This project follows a **structured, analyst-style EDA workflow**, covering:
- Univariate analysis (numerical & categorical)
- Bivariate analysis (numerical–numerical, numerical–categorical, categorical–categorical)
- Outlier detection and data quality assessment

---

## 📂 Dataset
- **Source:** Kaggle – Marketing Data Analysis  
  🔗 https://www.kaggle.com/code/meghana007d/marketing-data-analysis

- **Description:**  
  The dataset contains information about customers, including:
  - Demographics (Age, Education, Marital Status, Country)
  - Financial status (Income)
  - Purchase behavior across product categories
  - Purchase channels (Web, Store, Catalog)
  - Campaign acceptance and response indicators

- **Rows:** ~2,200 customers  
- **Columns:** 28 features

---

## 🧹 Data Preprocessing & Feature Engineering
Key preprocessing steps were performed before analysis:

- **Handling missing values**  
  - Income column contained missing values, which were carefully addressed to avoid bias.

- **Feature engineering**  
  - Created an `Age` feature from `Year_Birth`.
  - Removed unrealistic age values (> 85 years) identified as data quality issues.

- **Outlier treatment**  
  - Detected and removed extreme income outliers that distorted visual interpretation.

- **Data type validation**  
  - Ensured correct identification of numerical, categorical, and binary variables for proper analysis.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis

**Numerical Variables**
- Used descriptive statistics (mean, median, std, min, max)
- Visualized distributions using:
  - Histograms
  - Boxplots
- Identified skewness and outliers in income, age, spending, and purchase counts

**Categorical Variables**
- Analyzed frequency and percentage distribution
- Visualized using bar charts and count plots
- Key categories analyzed:
  - Education
  - Marital Status
  - Country
  - Campaign response indicators

---

### 🔹 Bivariate Analysis

**Numerical vs Numerical**
- Used correlation analysis and scatter plots
- Key relationships explored:
  - Income vs Spending behavior
  - Recency vs Purchase frequency
- Observed mostly weak linear correlations, highlighting diverse customer behavior

**Numerical vs Categorical**
- Used group statistics and boxplots
- Compared numerical features across:
  - Education levels
  - Marital status
  - Campaign response groups

**Categorical vs Categorical**
- Used cross-tabulation and heatmaps
- Analyzed campaign response rates across customer segments

---

## 🔍 Key Insights
- Income and spending behavior show **high variability**, with a small group of premium customers
- **Recency** is a strong indicator of customer engagement
- Customers with **higher education levels** tend to have higher median income
- Campaign response rates vary significantly across customer segments
- Most numerical relationships are **non-linear**, emphasizing the need for segmentation over simple correlation

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn
- **Tools:** Jupyter Notebook, VS Code

---

## 📁 Project Structure
```
MARKETING CUSTOMER DATA ANALYSIS/
├── Marketing data/                           # Dataset
│   └── marketing_data.csv
├── marketing_data_analysis.ipynb             # Main EDA notebook
├── sample_output/                            # Generated plots
│   ├── age_distribution.png
│   ├── campaign_response_heatmap.png
│   ├── education_based_spanding.png
│   └── income_distribution.png
└── README.md                                 # Project documentation
```

---

## 🚀 Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Outlier detection and treatment
- Statistical interpretation
- Business-focused data storytelling
- Visualization for insight generation

---

## 📌 Conclusion
This project demonstrates a **complete, structured EDA workflow** commonly used in real-world data analytics and data science roles. The insights derived can directly support **marketing strategy optimization and customer targeting decisions**.

---

## 👨‍💻 Author

**Dharm Dobariya**  
📧 Email: dharmdobariya7016@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/dharm-dobariya-42408134b

---

⭐ If you found this project useful, feel free to star the repository!


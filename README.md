# AI-JOB-MARKET
The Job market dataset provides insights into the current trends and patterns in the artificial intelligence job industry.

# Overview
The project performs data cleaning and Exploratory Data Analysis(EDA) on a salary dataset.
The goal is to understand how different factors like **experience level,company size,job role, and location** affect salaries.
This analysis helps in identifying patterns, trends, and key insights from dataset.
---
## 📁 Dataset Information
- Dataset Name: AI Job Market Dataset
- Total Records: 10,000+ entries
- Total Features: 10+ columns

### Key Columns:
- job_title – Role of the employee  
- salary – Salary of the employee  
- experience_level – Entry, Mid, Senior, Executive  
- employment_type – Full-time, Part-time, Contract  
- company_size – Small (S), Medium (M), Large (L)  
- company_location – Location of the company  
- education_level – Qualification  
- skills – Skills required  

---

## 🧹 Data Cleaning Steps
The following cleaning steps were performed:

- Checked for missing values using isnull()  
- Removed null values using dropna()  
- Identified and removed duplicate records  
- Standardized column names (lowercase, no spaces)  
- Verified and corrected data types  
- Checked for inconsistencies in categorical values  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Distribution of salary using histogram  
- Count of employees by experience level  
- Distribution of company sizes  

### 🔹 Bivariate Analysis
- Salary vs Experience Level  
- Salary vs Company Size  
- Salary vs Employment Type  

### 🔹 Multivariate Analysis
- Correlation heatmap between numerical variables  
- Grouped analysis using groupby()  

---

## 📈 Visualizations Used
- Histogram (Salary distribution)  
- Bar plots (Category comparisons)  
- Box plots (Outlier detection)  
- Heatmap (Correlation analysis)  

---

## 🔍 Key Insights
- Senior and executive-level employees earn significantly higher salaries   
- Medium and large companies tend to offer higher salaries  
- Salary distribution is right-skewed (more lower values, fewer very high values)  
- Certain job roles consistently offer higher pay  
- Experience level is one of the most important factors affecting salary  
---

## 🛠️ Tools & Technologies
- Python 🐍  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab
---

## 📌 Conclusion
The project successfully demonstrates how data cleaning and EDA can uncover meaningful insights from raw data.  
It highlights the importance of experience, company size, and job role in determining salaries.
---

## 🚀 Future Scope
- Build machine learning models for salary prediction  
- Perform deeper analysis on skills vs salary  
- Use larger and more diverse datasets  

---

## 👤 Author
Aryaka lalkrishna c p


- Your Name

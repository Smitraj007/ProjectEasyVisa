# 🛂 Easy Visa Prediction using Machine Learning

## 📌 Project Overview
Business communities in the United States face high demand for human resources, but identifying and attracting the right talent remains a challenge.  
The **Immigration and Nationality Act (INA)** permits foreign workers to work in the US on a temporary or permanent basis, while ensuring protection for US workers.  

The **Office of Foreign Labor Certification (OFLC)** processes job certification applications for employers seeking to bring foreign workers into the US. With the rising number of applications each year, manual review has become tedious.  

This project aims to build a **Machine Learning classification model** to assist OFLC in shortlisting candidates with higher chances of visa approval.

---

## 🎯 Objectives
- Facilitate the process of visa approvals using data-driven insights.  
- Recommend suitable applicant profiles for certification or denial.  
- Identify key drivers that significantly influence visa case status.  

---

## 📊 Dataset Description
The dataset contains attributes of employees and employers:

- `case_id`: Unique ID of each visa application  
- `continent`: Continent of the employee  
- `education_of_employee`: Education level of the employee  
- `has_job_experience`: Job experience (Y/N)  
- `requires_job_training`: Requires job training (Y/N)  
- `no_of_employees`: Number of employees in the employer's company  
- `yr_of_estab`: Year employer’s company was established  
- `region_of_employment`: Intended region of employment in the US  
- `prevailing_wage`: Average wage paid to similarly employed workers  
- `unit_of_wage`: Unit of prevailing wage (Hourly, Weekly, Monthly, Yearly)  
- `full_time_position`: Full-time position (Y/N)  
- `case_status`: Visa case outcome (Certified/Denied)  

---

## 🔍 Exploratory Data Analysis (EDA) Focus
Key guiding questions for analysis:
- Distribution of visa case statuses (certified vs. denied).  
- Impact of education level on approval rates.  
- Effect of prior job experience on approval.  
- Relationship between prevailing wage and approval likelihood.  
- Regional differences in approval rates.  
- Influence of company size (number of employees).  
- Approval rates across continents.  

⚠️ Beyond these basics, deeper trends and relationships should be uncovered for full credit.

---

## 🛠️ Methodology
1. **Data Preprocessing**  
   - Handling missing values, encoding categorical variables, scaling wages.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizations and statistical tests to identify key drivers.  

3. **Model Building**  
   - Classification models (Logistic Regression, Decision Trees, Random Forest, etc.).  
   - Optional: XGBoost (can be skipped if time complexity is an issue).  

4. **Model Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.  
   - Comparison of models to select the best performing one.  

5. **Insights & Recommendations**  
   - Highlight significant features influencing visa approval.  
   - Provide actionable recommendations for OFLC.  

---

## 📌 Submission Guidelines
- Submit a **single Python notebook in HTML (.html) format**.  
- Ensure code runs sequentially from start to end.  
- Add observations and insights for each step.  
- Cover all rubric sections with visible outputs.  
- Plagiarism will result in zero marks.  
- Late submissions may not be accepted or will attract penalties.  

---

## ✅ Important Notes
- XGBoost is optional; skipping it will not affect marks.  
- If code is correct but not executed, **50% marks will be deducted** for that section.  
- Connect with the Program Manager in case of confusion.  

---

## 🚀 Power Ahead!
This project combines **data science techniques** with **real-world policy applications** to streamline visa approval processes and support workforce planning in the United States.

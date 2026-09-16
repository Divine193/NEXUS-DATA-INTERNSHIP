# Project Title: Healthcare Demographics & Cost Exploratory Analysis

## 📌 Project Overview
This project conducts an in-depth exploratory data analysis (EDA) on a healthcare dataset to uncover underlying patterns in patient demographics and admissions, Medical conditions, insurance coverage and medical  billing. The goal is to provide a clear visual narrative of what drives healthcare costs.

## 🎯 Objectives
*   Clean and preprocess healthcare records for accurate analysis.
*   Identify key demographic trends like medical condition, Admission types and their impact on medical charges.
  

## 🛠️ Tech Stack & Tools
*   **Tools:** Excel
*   **Language:** Python
*   **Environment:** Jupyter Notebook
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
*   **Documentation:** Comprehensive visual report provided in `Analysis_report.pdf`

## 📊 The Dataset
*   **Source:** Kaggle
*   **Size:** 55,500 rows, 15 columns
*   **Variables Analyzed:** `age`, `gender`, `Admission type`, `Medical Condition`, `Billing Amount`, `Test Results`

## ⚙️ Methodology (The EDA Process)
1.  **Data Wrangling:** Initial Cleaning was done with Excel where change the case on the name column to Proper Case 
2.  **Univariate Analysis:** Examining the distribution of individual variables like Age and Billing.
3.  **Bivariate & Multivariate Analysis:** Investigating relationships between multiple variables, such as how medical conditions affect billing amount, how admission type affects billing amount and distribution of medical conditions by age groups
4.  **Feature Engineering (Optional):** grouping ages into 'Age Brackets', splitting the date of admission column into three different columns namely; month of admission, year of admission, and day of the week of admission.

## 💡 Key Findings & Visual Insights
*   **Finding 1:** The elderly(66+) happened to be the most common visitors in the hospitals, They account for 29% of the total number of patients in the dataset. This also contributed to the fact that Diabetes and Arthritis are the most common diseases that were treated.
*   **Finding 2:**  It was observed that certain Blood groups are more susceptible to certain diseases more than others, for example AB+ and A- are more prone to having hypertension more than other blood groups(hypertension counts for both blood groups were approximately 1.5% above the other blood groups
*   **Finding 3:** Obesity and Diabetes happened to be the most expensive medical conditions based on medical billing. This can be due to the fact that these diseases may need a dietician which is quite expensive.

*(Note: The full insights can be found in the PDF report in the repo).*

## 🚀 How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone [https://github.com/Divine193/NEXUS-DATA-INTERNSHIP.git](https://github.com/Divine193/NEXUS-DATA-INTERNSHIP.git)

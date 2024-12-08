# Capstone Projects Repository  
Welcome to my GitHub portfolio! This repository showcases the capstone projects from my Master's in Business Analytics program at the **University of Utah**.  

---

## About Me  
👋 Hi, I’m **Joseph Pushnam**, a Business Analytics student with a passion for solving complex problems through data-driven insights. This repository highlights my work on the **Home Credit Default Risk Project**, where I explore predictive modeling techniques to address real-world business challenges.  

---

## Featured Project: **Home Credit Default Risk**  

# Home Credit Default Risk Analysis

## Summary of the Business Problem and Project Objective
The goal of this project is to predict loan repayment defaults, which is crucial for financial institutions aiming to minimize risks and extend credit responsibly. Using a dataset with diverse client features, such as age, income, and credit details, the project focuses on building machine learning models to predict the likelihood of default. The target variable (`TARGET`) is binary, with 0 indicating no default and 1 indicating default. Exploratory analysis revealed significant patterns in features like `DAYS_BIRTH` (age), `AMT_INCOME_TOTAL` (income), and `NAME_CONTRACT_TYPE`, highlighting their potential predictive power. For example, clients with longer `DAYS_BIRTH` (indicating older age) showed a lower likelihood of default.

---

## Group's Solution to the Business Problem
The project used a systematic approach to preprocessing and modeling. Missing data, particularly in critical features such as `OWN_CAR_AGE` and `AMT_ANNUITY`, was addressed through imputation methods. Feature transformations were applied, including converting `DAYS_BIRTH` into `age_years`, to enhance model interpretability.

The machine learning pipeline included Logistic Regression and Random Forest models, evaluated using metrics like Area Under the Curve (AUC) and accuracy. Logistic Regression, serving as a baseline, achieved an AUC of **0.682**. The Random Forest model improved performance with an AUC of **0.739**, indicating its ability to capture non-linear relationships in the data.

---

## Personal Contributions to the Project
My primary contributions included conducting Exploratory Data Analysis (EDA), cleaning missing data, and training predictive models. Through EDA, I identified patterns in features such as `DAYS_BIRTH` and `AMT_CREDIT`, which were instrumental in feature engineering. I also handled missing values for critical variables like `OWN_CAR_AGE` to ensure data quality. In the modeling phase, I trained and evaluated Logistic Regression and Random Forest models. The Random Forest model demonstrated superior performance, with an improvement of **8%** in AUC over Logistic Regression, reflecting its robustness in handling complex data.

---

## The Business Value of the Solution
The developed models provide financial institutions with actionable insights to manage credit risk effectively. The Random Forest model, with an AUC of **0.739**, enables the identification of high-risk clients, reducing potential defaults and improving lending strategies. For example, older clients (as determined by the `DAYS_BIRTH` feature) and those with lower income-to-credit ratios were less likely to default, helping segment clients based on risk profiles. This solution has the potential to decrease default rates by an estimated **10%–15%**, boosting profitability and fostering financial inclusion.

---

## Difficulties Encountered
The project faced significant challenges, particularly in addressing missing data and class imbalance. Critical features such as `OWN_CAR_AGE` and `AMT_ANNUITY` had up to **40%** missing values, requiring careful imputation strategies to maintain data integrity. Additionally, the target variable (`TARGET`) was highly imbalanced, with only **8%** of cases indicating default. Although this imbalance posed challenges for model performance, strategies to mitigate its impact are still being explored.

---

## What I Learned in the Project
This project provided valuable experience in handling real-world data challenges, including missing data and class imbalance. I learned to preprocess datasets effectively, engineer meaningful features, and evaluate models using metrics such as AUC. Through this analysis, I gained insights into how to translate technical results into actionable business decisions. The project also enhanced my understanding of how predictive modeling can address critical problems in the financial industry, such as reducing default rates and optimizing credit strategies.


---

## What's Inside  
📂 **Individual Notebooks**:  
- **EDA.ipynb**: Data exploration and visualization.  
- **Modeling.ipynb**: Feature engineering, model training, and evaluation.  

📊 **Visualizations**:  
- Charts and graphs demonstrating data trends and model performance.  

---

## Why This Matters  
The work here demonstrates my ability to:
- Tackle real-world business problems using advanced analytics.  
- Perform reproducible data science with tools like R and Python.  
- Communicate insights effectively through clean visualizations and documentation.  

---

## What's Next  
🚀 I'm excited to continue building this repository and adding more content as I refine my notebooks. Stay tuned for detailed explanations, results, and insights!  

Feel free to explore and reach out if you'd like to discuss the project or share feedback!  

---

### Connect with Me  

<img src="https://github.com/user-attachments/assets/f93c176e-6343-4059-b163-708f9e07c329" alt="emoji" style="width: 1.3em; height: 1em; vertical-align: middle;"> **Email**: [josephpushnam@gmail.com](mailto:josephpushnam@gmail.com)  
<img src="https://github.com/user-attachments/assets/5faf05be-d861-4325-852d-608701e5e025" alt="emoji" style="width: 1em; height: 1em; vertical-align: middle;"> **LinkedIn**: [linkedin.com/in/joseph-pushnam](https://linkedin.com/in/joseph-pushnam)  



---

### Technical Stack  
- **Programming**: R, Python  
- **Tools**: GitHub, RStudio, Jupyter Notebook  
- **Libraries**: `tidyverse`, `scikit-learn`, `xgboost`  

---

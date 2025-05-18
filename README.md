# Student-Performance Analysis using Python

This project conducts an in-depth statistical analysis of student performance data, focusing on modeling Grade Point Average (GPA) using Ordinary Least Squares (OLS) regression. The analysis includes comprehensive diagnostic tests to validate the regression model and ensure its reliability.

📁 Repository Contents

Data_Analysis.ipynb: Jupyter Notebook containing the Python code for data preprocessing, exploratory data analysis (EDA), regression modeling, and diagnostic testing.

Student_performance_data_.csv: The dataset used for analysis, containing various features related to student performance.

Student Performance Project.pdf: A detailed report summarizing the methodology, analysis, results, and conclusions drawn from the study.

README.md: This file, providing an overview of the project.

📈 Analysis Overview

The primary objective of this project is to model students' GPA based on various predictors and assess the validity of the model through several statistical tests:

OLS Regression: Establishes the relationship between GPA and independent variables.

t-test: Evaluates the significance of individual regression coefficients.

F-test: Assesses the overall significance of the regression model.

Durbin-Watson (DW) Test: Detects the presence of autocorrelation in the residuals.

Jarque-Bera (JB) Test: Tests whether the residuals are normally distributed.

Skewness and Kurtosis: Measures the asymmetry and peakedness of the residual distribution.

Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC): Provides metrics for model selection, balancing model fit and complexity.

🛠️ Getting Started

To replicate the analysis:

Clone the Repository:

bash
Copy
Edit
git clone https://github.com/sayaleej/Student-Performance-Data-DATA-294P-.git
cd Student-Performance-Data-DATA-294P-
Install Dependencies:
Ensure you have the necessary Python packages installed. You can use the following command:

bash
Copy
Edit
pip install pandas numpy statsmodels matplotlib seaborn
Run the Notebook:
Open Data_294P_Code.ipynb in Jupyter Notebook or any compatible environment to explore the analysis.

📄 Dataset Description

The dataset Student_performance_data_.csv includes various features that may influence student GPA. While specific variable descriptions are not provided, typical features in such datasets may include:

Demographic Information: Age, gender, ethnicity.

Academic Records: Previous grades, attendance, study hours.

Socioeconomic Factors: Parental education, family income.

Behavioral Aspects: Participation in extracurricular activities, disciplinary records.

Note: For precise variable definitions, please refer to the dataset or accompanying documentation.

📊 Key Findings

Significant Predictors: Certain variables showed a strong correlation with GPA, indicating their potential impact on academic performance.

Model Validity: Diagnostic tests confirmed the reliability of the regression model, with residuals displaying normal distribution and no significant autocorrelation.

Model Selection: AIC and BIC values were used to compare different models, aiding in selecting the most appropriate one.

For detailed results and interpretations, refer to the Student Performance Project.pdf report.

📚 References
Statistical Methods:

OLS Regression

Durbin-Watson Test

Jarque-Bera Test

AIC and BIC

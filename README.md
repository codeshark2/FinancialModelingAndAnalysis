# finModeling

Objective: Implement and analyze various financial models for chosen financial applications.
1. ARIMA
2. PCA
3. SVM
4. SVR

1) ARIMA:

Problem Statement:: "How can we effectively predict the weekly average stock prices of Apple Inc. using an ARIMA (AutoRegressive Integrated Moving Average) model based on historical data for the purpose of time series forecasting, in order to assist investors and stakeholders in making informed financial decisions?"

Data Description: : Dataset: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/ai-for-finance/data/AAPL10Y.csv for the analysis and prediction. This is AAPL company's 10 years share price (in usd) data from 2009 to 2019.

Reference code: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/ai-for-finance/solution/arima_model.ipynb



2) PCA:

Problem Statement: "How can we effectively employ Principal Component Analysis (PCA) as a mathematical technique to compress high-dimensional data into a lower-dimensional representation, with the objective of simplifying data analysis processes and gaining insights from the reduced dataset?"

Data Description:: I used "Borsa Istanbul 100" a.k.a. "Bist100" stock market index symbols. It is an index of Turkey stocks that covers top 100 biggest components. Gathered 5 basic financial ratios for each symbol around internet and here is the raw result (ticks.raw.csv)

Datasets are available on the same github repo mentioned below

Reference code: https://github.com/diwsi/Principle-Component-Analysis-for-Stock-Markets/



3) SVM:

Problem Statement: Can a Support Vector Machine (SVM) model be developed to accurately predict the approval or rejection of bank loan applications, based on various applicant attributes, in order to enhance the loan approval process and reduce risks associated with granting loans?

Data Description:: The "loan_decision.csv" dataset consists of a diverse range of attributes related to loan applicants and loan approval outcomes. Each entry is uniquely identified by a "Loan_ID." The dataset includes demographic information such as "Gender" and "Marital Status," as well as details about financial standing, such as "ApplicantIncome," "CoapplicantIncome," and "LoanAmount." Additionally, it captures educational background with the "Education" feature and employment status with "Self_Employed." The "Dependents" column reflects the number of dependents associated with each applicant. Loan-specific attributes encompass "Loan_Amount_Term," "Credit_History," and "Property_Area." Notably, "Loan_Status" serves as the target variable, indicating whether a loan application was approved ('Y') or not approved ('N'). This dataset is valuable for exploring factors influencing loan approval and developing predictive models for the loan decision process.

Reference code from github - https://github.com/Devbijwe/Loan-Approval-Prediction-classifications/




4) SVR:

Problem Statement: Predicting the stock price of a company(Apple) using Support Vector Regression model.

Data Description: : We use the following data: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/ai-for-finance/data/AAPL10Y.csv for the analysis and prediction. This is AAPL company's 10 years share price (in usd) data from 2009 to 2019.

Code refernce from github: https://github.com/microsoft/ML-For-Beginners/blob/main/7-TimeSeries/3-SVR/README.md

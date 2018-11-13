# MS Data Science Capstone Project: Predicting the Student Loan Repayment

This capstone project was part of **Microsoft Professional Program in Data Science**. 

The task of the project is to:
- present our findings from the analysis of the data related to loans given to students at United States institutions of higher education, and 
- create a model to predict the repayment rate for the student loans. 

Student loan is a complex data issue. A student's ability to repay loans depends on the job they get after graduation. This in turn depends on the school they went to, the degree they earned, the area they live in, their family circumstances, and how much money they borrowed. By modeling what percent of students repay their loans, an attempt is made to better understand the properties of schools that make them better or worst investments, in terms of whether attending that school increases the probability that the students will get a job good enough to repay their loans.

The dataset consists of 8705 observations (identified by a unique identifier “row_id”) and 443 features (excluding row_id and repayment_rate). Each row in the dataset represents a United States institution of higher education and a specific year (i.e. two particular years, denoted by “year_a” and “year_b”). 

Our goal is to predict the variable “**Repayment Rate**”. It is defined as the approximate percent of students that make active repayments on their loans. For example, a value 25 means that about 25% of the students have been decreasing the balance on their loans through repayment.

After exploring the data by calculating summary and descriptive statistics, and by creating visualizations of the data, several relationships between the features and the Repayment Rate are identified. We then create a model to classify the USA institutions into two classes based on whether the repayment rate is lower or higher than the average repayment rate. Finally a regression model to predict the Repayment Rate from its features is created. The performance metric considered in this regression problem is Root Mean Squared Error (RMSE).

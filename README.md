# credit-risk-classification
---
**This analysis is divided into the following subsections:**
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report
---
## 1-Split the Data into Training and Testing Sets
---
**In this section we have completed the following steps:**
* Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
* Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
* Split the data into training and testing datasets by using train_test_split.
Create a Logistic Regression Model with the Original Data
---
  <img width="882" alt="Screenshot 2024-07-23 at 10 39 43 AM" src="https://github.com/user-attachments/assets/74c34202-bb63-41b4-9281-9be11104e388">
---
<img width="910" alt="Screenshot 2024-07-23 at 12 08 50 PM" src="https://github.com/user-attachments/assets/f8767ba1-ca44-494f-a63a-2367d3e53755">

## 2-Create a Logistic Regression Model with the Original Data
---
**In this section we have completed the following steps:**
* Fit a logistic regression model by using the training data (X_train and y_train).
* Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
* Evaluate the model’s performance by doing the following:
- Generating a confusion matrix.
---
 <img width="322" alt="Screenshot 2024-07-23 at 10 38 49 AM" src="https://github.com/user-attachments/assets/3beeb1e7-ec85-4f6a-bd33-b43313c99d06">
---

- Printing the classification report.
---
<img width="952" alt="Screenshot 2024-07-23 at 10 37 58 AM" src="https://github.com/user-attachments/assets/9b0a67f5-1521-449f-93d5-93a10190961a">

* Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
---
## 3-Write a Credit Risk Analysis Report
---
**In this section we have completed the following steps:**
Written a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework, ensuring that it contains the following:
- An overview of the analysis: Explain the purpose of this analysis.
- The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
- A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

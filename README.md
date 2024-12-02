# credit-risk-classification

* [ ] **Overview of the Analysis**

The purpose of this analysis is to assess the credit risk of loan applicants using machine learning techniques, specifically through logistic regression. This dataset contains various financial attributes of loans along with the loan_status, indicating whether a loan is healthy or high-risk. By building a predictive model, we aim to identify high-risk loans, which could be beneficial for a company in making informed lending decisions and minimizing potential losses.

The main objectives of this analysis include:

* Developing a machine learning model to predict loan risk status.
* Evaluating the model’s performance to understand its effectiveness in classifying loans as healthy or high-risk.
* Providing insights and recommendations based on the model's accuracy and other performance metrics.

Steps Taken:

Data Preprocessing: We read the data, cleaned it, and split it into features (X) and target  labels (y), where y is the loan_status.

Model Training: Split the data into training and testing sets using train_test_split from sklearn.

Model Evaluation: We evaluated the model using a confusion matrix and classification report to assess its accuracy, precision, and recall.

Risk Assessment: Based on the performance of the model, we provide insights on the model's effectiveness in predicting high-risk loans.

* [ ] **Results**

Model Performance Metrics:

1. Accuracy Score:

The accuracy score of the model reflects the proportion of correct predictions (both healthy and high-risk loans) out of all predictions made.

The model achieved an accuracy score of 99%.

2. Precision Score:

Precision measures the accuracy of positive predictions (high-risk loans).

Measures the model's ability to correctly identify high-risk loans (positive predictions).

The precision score for high-risk loans is 84%.

3. Recall Score:

Recall measures how well the model identifies all actual positive cases (true high-risk loans).

The recall score for high-risk loans is 94%.

   4.Confusion Matrix:

The confusion matrix provides a summary of the model’s true positives, false positives, true negatives, and false negatives.

Confusion Matrix: [[True Negative, False Positive], [False Negative, True Positive]]

Confusion Matrix:
[[18655,    110],
 [   36,   583]]

* [ ] **Summary**

The logistic regression model performed reasonably well in predicting the loan status, with accuracy, precision, and recall indicating its capacity to classify loans into healthy or high-risk categories. Below are insights and recommendations for its use in a company setting:

* **Recommendation** : Given the model's performance, it is recommended for company use in supporting initial credit risk assessments, especially if identifying high-risk loans is prioritized. The model’s high precision 84% for high-risk loans suggests that it correctly identifies a significant portion of truly risky loans, which is crucial for reducing financial losses.
* **Justification** : While the recall score of 94% indicates the model is highly effective in capturing actual high-risk cases, the slight trade-off in precision means there are a few false positives (loans incorrectly labeled as high-risk). However, this approach still provides valuable risk assessment for minimizing potential defaults.
* **Future Considerations** : For further improvements, the company may consider:
* Testing alternative models (e.g., random forest, XGBoost) to enhance prediction accuracy.
* Adjusting logistic regression parameters to improve recall if correctly identifying all high-risk loans is prioritized.
* Using the logistic regression model in combination with other algorithms as part of a more comprehensive risk assessment pipeline.

  In conclusion, the logistic regression model offers a reasonable and effective approach to predicting loan status based on financial attributes, providing actionable insights into applicant risk levels. For applications where predicting high-risk loans is critical, this model could serve as a robust starting point for the company’s credit risk assessment strategy.

* [ ] **Technologies Used**

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

* [ ] **References** : Class Materials (Zoom cloud recordings )

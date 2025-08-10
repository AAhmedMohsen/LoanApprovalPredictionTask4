# Loan Approval Prediction – Project Steps

## 📌 Steps Performed in This Project

1. **Load the Dataset**
   - Imported `loan_approval_dataset.csv` using Pandas.

2. **Data Cleaning**
   - Checked for missing values and handled them.
   - Encoded categorical variables using label encoding / one-hot encoding as needed.

3. **Feature Scaling**
   - Applied `StandardScaler` to numerical features for better model performance.

4. **Train-Test Split**
   - Split the dataset into training (80%) and testing (20%) sets using `train_test_split`.

5. **Handle Class Imbalance**
   - Applied **SMOTE** (Synthetic Minority Oversampling Technique) on the training set to balance the target classes.

6. **Model Training**
   - Trained **Logistic Regression** model on the balanced dataset.
   - Trained **Decision Tree Classifier** model on the balanced dataset.

7. **Model Evaluation**
   - Predicted results on the test set for both models.
   - Calculated:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
   - Compared the performance of Logistic Regression and Decision Tree.

8. **Result Conclusion**
   - Determined which model performed better based on evaluation metrics.

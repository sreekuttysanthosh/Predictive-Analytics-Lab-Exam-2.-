# Predictive-Analytics-Lab-Exam-2.-
Predictive Analytics Lab Exam-2. 
#Objective
perform classification task using Logistic regression 
#Dataset 
dataset contains :
-feature 1 and feature2 as input variables
-target as output varaible(Yes/No)
The target variable was converted into numerical form (Yes = 1, No = 0) after cleaning.
## Exploratory Data Analysis
- Checked dataset structure and summary statistics
- Handled inconsistencies in the target column
- Visualized class distribution
- Plotted scatter plot to understand data distribution
- Generated correlation matrix
---
## Data Preprocessing
- Cleaned target values by removing spaces and converting to lowercase
- Converted categorical target into numeric values
- Removed invalid or missing entries
---
## Model
Logistic Regression was used for classification.
Reason:
- Suitable for binary classification
- Provides a clear linear decision boundary
- Easy to interpret
---
## Decision Boundary
The decision boundary was plotted using the two features.
It shows how the model separates the two classes.

Observation:
- The boundary is linear
- Some overlap between classes is observed

---
## Model Evaluation
The model was evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report
Results:
- The model achieved good accuracy
- Most instances were classified correctly

---

## Limitations
- Logistic regression assumes a linear relationship
- The dataset shows overlapping classes
- Some misclassification occurs due to non-linear patterns

---

## Conclusion
Logistic Regression was successfully applied to classify the dataset.
The model performs reasonably well, though some limitations exist due to overlapping data.

result intreprtaion 
The model was evaluated using accuracy, confusion matrix, and classification metrics.
The model achieved an accuracy of76%.
The confusion matrix shows that the majority of instances are correctly classified, with some misclassifications due to overlapping data.
Precision and recall values indicate that the model performs reasonably well in identifying both classes.
The F1-score shows a balanced performance between precision and recall.

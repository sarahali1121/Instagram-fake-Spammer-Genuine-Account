# Instagram-fake-Spammer-Genuine-Account
Title: Instagram Account Classification: Detecting Fake & Genuine Users using Decision Trees
Submitted by: Sara
1. Introduction
With the rise of social media, fake and spam accounts have become a growing concern. Identifying such accounts is crucial for platform security and user trust. This project focuses on classifying Instagram accounts as genuine or fake using a Decision Tree Classifier.
2. Objective

Analyze Instagram user account features

Visualize patterns of fake vs genuine users

Build a model to classify accounts accurately

Interpret important features affecting classification
3. Tools & Technologies Used

Language: Python

Libraries: pandas, seaborn, matplotlib, scikit-learn

Model: Decision Tree Classifier

IDE: Google Colab
4. Dataset Description
The dataset includes two CSV files — training and testing — containing numerical features of Instagram accounts, such as:

Number of followers

Following count

Post count

Other behavioral metrics

 Target variable: fake (0 = Genuine, 1 = Fake)
5. Exploratory Data Analysis (EDA)
5.1. Fake vs Genuine Distribution

 Countplot showed balanced data across both classes.
5.2. Correlation Matrix

 Heatmap displayed feature relationships, helping detect multicollinearity.
5.3. Histograms & Scatter Matrix

 Histogram revealed spread of features.

 Scatter matrix helped spot patterns based on class (fake vs genuine).
6. Model Development
6.1. Classifier Used

 Decision Tree Classifier for transparency and easy visualization.
6.2. Data Split

 Separate train and test datasets were used for training and evaluation.
6.3. Evaluation Metrics

 Accuracy: 89.1%

 Confusion Matrix:
[[55 5]
[ 8 52]]

 Precision/Recall (Class 0 Genuine): 0.87 / 0.92

 Precision/Recall (Class 1 Fake): 0.91 / 0.87
Interpretation: The model performs very well for both classes, with high precision and recall.
7. Feature Importance & Model Visualization

 Bar plot showed which features contribute most to the classification.

 Full decision tree was visualized for explainability.

 This helps understand why the model classifies an account as fake/genuine.
8. Conclusion
The decision tree classifier successfully identified fake vs genuine accounts on Instagram with high accuracy and interpretability. Visualization of the tree helped understand decision paths clearly, making it suitable for moderation systems or social media analytics.
9. Future Work

 Apply ensemble models like Random Forest or XGBoost for further improvement

 Add textual/NLP features from bios or posts

 Address adversarial account behavior with time-series data

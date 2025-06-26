Phishing URL Detection using Machine Learning
Overview
This project presents a robust approach to detecting phishing URLs using various machine learning models. Phishing attacks remain a significant cybercrime, aimed at deceitfully acquiring sensitive user information such as credentials and financial details. These malicious activities frequently target online payment platforms, webmail services, financial institutions, and cloud storage providers. While traditional methods like blacklisting offer ease of implementation, they often fall short in identifying emerging phishing threats. This research addresses these limitations by leveraging machine learning algorithms to effectively identify and mitigate phishing websites.

Methodology and System Workflow
The overall flow of this thesis work follows a structured approach:

Understanding Phishing URLs: Initial phase focused on comprehending the nature of phishing URLs and the imperative for their detection.

Literature Review: Comprehensive study of existing techniques and research in phishing detection.

Dataset Collection: Gathering and preparing the 'Website Phishing dataset' for model training and evaluation.

Experimentation: Conducting experiments with different machine learning algorithms.

Model Evaluation: Assessing the performance of the trained models.

Thesis Writing: Documenting the entire research process and findings.

The proposed system workflow, from dataset loading to prediction, involves:

Load Dataset: Ingesting the raw dataset.

Data Preprocessing: Cleaning, transforming, and preparing the data for model consumption.

Finding Correlation in Dataset: Analyzing relationships between features in the dataset.

Train-Test Split: Dividing the dataset into training and testing subsets to ensure unbiased model evaluation.

Machine Learning Model Training: Training various models (XGBoost, Decision Tree, Logistic Regression, K-Neighbors Classifier, RandomForest Classifier) on the training dataset.

Prediction: Using the trained models to make predictions on the testing dataset.

Models Used
This study evaluates the performance of the following machine learning algorithms for phishing URL detection:

XGBoost (Extreme Gradient Boosting)

Decision Tree

Logistic Regression

K-Nearest Neighbor (KNN) Classifier

Random Forest Classifier

Dataset
The models were trained and evaluated using the Website Phishing dataset.

Research Findings and Performance
Our comprehensive analysis reveals that among the evaluated models, the XGBoost classifier consistently demonstrated superior performance in detecting phishing websites.

Here's a summary of the model performance: 




The XGBoost classifier achieved the highest test accuracy of 85.2%, along with strong precision, recall, and f1-score, confirming its efficacy as the best classifier for this task.
Visualizations
Confusion Matrix: An example confusion matrix for one of the models illustrates its ability to distinguish between "Fake" (phishing) and "Real" (legitimate) URLs.

Receiver Operating Characteristic (ROC) Curve: The ROC curve visualizes the diagnostic ability of our machine learning models, showing the trade-off between the true positive rate and the false positive rate across different threshold settings. XGBoost shows a favorable curve, indicating its robust performance.

Key Features
Comprehensive implementation and evaluation of five popular machine learning algorithms for phishing URL detection.
![Capture](https://github.com/user-attachments/assets/aecee2b0-b932-4dcd-8a14-ba6caab9468a)

Detailed performance metrics (accuracy, precision, recall, f1-score) for each model.
![image](https://github.com/user-attachments/assets/a350edae-b04e-4a7e-b18a-a3c6ff660be7)


Identification of XGBoost as the top-performing model with high accuracy.
![image](https://github.com/user-attachments/assets/2ced4a84-08be-4519-aede-78385ce1263a)

Visualizations including Confusion Matrix and ROC Curves to support findings. 

![rock curve](https://github.com/user-attachments/assets/324a49c3-6e6e-490c-8849-33405a9c2f1f)

# Credit Card Fraud Detection

## 1. Introduction
With the rapid development of digitization and information technology, credit cards have become the predominant payment method. However, the surge in online transactions, especially during the Covid-19 pandemic, has led to an increase in credit card fraud. This poses a significant challenge for individuals, financial institutions, cybersecurity, and the government. In this project, we aim to address credit card fraud using data science methodologies to build predictive models for more efficient detection.

## 2. Related Work
Previous studies, such as Awoye’mi et al. (2017) and Maniraj et al. (2019), have explored credit card fraud detection using machine learning techniques. Awoye’mi et al. employed native Bayes, K-nearest Neighbor, and logistic regression, achieving the best accuracy with K-nearest Neighbor. Maniraj et al. focused on minimizing inappropriate fraud classification and achieved over 99.6% accuracy using anomaly detection algorithms.

## 3. Problem Definition and Algorithm
### 3.1 Task Definition
Credit card fraud involves the unauthorized use of credit or debit cards to fraudulently obtain money or property. We utilized a dataset containing credit card transactions to predict and detect fraudulent activities. The dataset is highly unbalanced, with only 0.172% of transactions labeled as fraud.

### 3.2 Algorithm Definition
Our approach involves:
1. Data cleaning: Using under-sampling techniques to address class imbalance.
2. Exploratory data analysis: Visualizing correlations between principal components obtained through PCA transformation.
3. Preprocessing data for modeling.
4. Building models: Employing classifiers like Logistic Regression, K Nearest Neighbors, Support Vector Classifiers, Random Forests, and Neural Networks.
5. Evaluating performance: Assessing models based on accuracy and recall.

## 4. Experimental Evaluation
### 4.1 Methodology
We applied both under-sampling and oversampling techniques, using classifiers like Logistic Regression, K Nearest Neighbors, Support Vector Classifier, and Random Forest Classifier. Evaluation metrics included precision, recall, f1-score, and accuracy.

### 4.2 Results and Discussion
Logistic Regression and Random Forest Classifiers achieved the highest accuracy (95%), with Logistic Regression having the highest ROC score (0.98). Logistic Regression performed exceptionally well in recall for fraudulent transactions. Neural Networks were also explored, with the oversampled dataset showing higher accuracy but lower recall compared to the undersampled dataset.

<p align="center">
  <img width="400" alt="image" src="https://github.com/Profzubbyd/Credit_card_fraud_detection/assets/46527701/f86e20d5-417c-4ed5-9714-8159a512086e">
  <img width="400" alt="image" src="https://github.com/Profzubbyd/Credit_card_fraud_detection/assets/46527701/cab4b84f-cdd9-48a4-ad4a-71d5a45c890f">
</p>

_Figure 1: Bar chart showing the unbalanced dataset (left) and the balanced dataset after under-sampling (right)._

<p align="center">
  <img width="800" alt="image" src="https://github.com/Profzubbyd/Credit_card_fraud_detection/assets/46527701/cda55c80-6d80-4114-8a47-c877ecdeae14">
</p>

_Figure 2: Confusion matrix of Logistic regression on oversampled vs other classifiers on the under-sampled dataset._

<p align="center">
  <img width="800" alt="image" src="https://github.com/Profzubbyd/Credit_card_fraud_detection/assets/46527701/7a363c31-6576-4bf5-9a46-cde6aba35639">
</p>

_Figure 3: Confusion matrix on a neural network model fitted on the under-sampled dataset._

<p align="center">
 <img width="800" alt="image" src="https://github.com/Profzubbyd/Credit_card_fraud_detection/assets/46527701/3a39adc0-f469-4e19-a084-fda67fac6585">
</p>

_Figure 4: Confusion matrix on a neural network model fitted on the over-sampled dataset._


## 5. Future Work
1. Addressing outliers to enhance model accuracy.
2. Evaluating classifiers on oversampled datasets with higher computing power.
3. Improving Neural Network models for better fraud prediction.

## 6. Conclusion
The Logistic Regression model demonstrated superior performance in detecting credit card fraud. It outperformed other classifiers, especially in recall for fraudulent transactions. Neural Networks on the undersampled dataset showed promising results, emphasizing the potential for effective fraud detection. These findings can benefit fraud detection agencies in mitigating credit card fraud.



## Bibliography
1. [Global Consumer Behaviour Trends - Online Shopping](https://www.weforum.org/agenda/2021/07/global-consumer-behaviour-trends-online-shopping/)
2. [J. O. Awoyemi et al. - "Credit card fraud detection using machine learning techniques: A comparative analysis"](https://ieeexplore.ieee.org/document/8123782)
3. [S P, Maniraj et al. - "Credit Card Fraud Detection using Machine Learning and Data Science"](https://www.ijert.org/research/credit-card-fraud-detection-using-machine-learning-and-data-science-IJERTV8IS090031.pdf)
4. [FBI - Credit Card Fraud](https://www.fbi.gov/scams-and-safety/common-scams-and-crimes/credit-card-fraud)
5. [SMOTE for Imbalanced Classification with Python](https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/)
6. [Credit Fraud || Dealing with Imbalanced Datasets](https://www.kaggle.com/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets)

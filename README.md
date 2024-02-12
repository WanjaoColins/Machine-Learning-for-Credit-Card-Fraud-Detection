![Image header](Fraud%20Image.png)

<h1 style="background-color: #cfe2f3; padding: 10px; color: black;"><b>Leveraging Machine Learning For Credit Card Fraud Detection</b></h1>

## Overview
This project focuses on developing a machine learning model to detect fraudulent transactions in financial datasets. By leveraging various classification algorithms, the aim is to accurately identify fraudulent activities while minimizing false positives and false negatives, thus safeguarding the financial institution's assets and customer trust.

## Resources Used
Editor: VS Code
Python Version: Python 3

## Packages Used
General purpose packages: itertools
Data manipulation packages: pandas, numpy
Data Visualization: seaborn, matplotlb
Machine Learning: sklearn

## Business and Data Understanding
Fraudulent transactions pose a significant threat to financial institutions and their customers in the digital economy. Despite numerous security measures, fraud continues to evolve, leading to financial losses and compromised trust. The chosen dataset reflects real-world credit card transactions, providing a relevant and challenging scenario for fraud detection modeling.

### Stakeholder Audience:
- Financial institutions concerned with minimizing fraud losses.

### Dataset Choice:
The dataset, obtained from [Kaggle](https://www.kaggle.com/code/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets/input) comprises credit card transactions, containing features such as transaction amount, time, and anonymized numerical variables derived from principal component analysis (PCA). The target variable indicates whether a transaction is fraudulent (1) or non-fraudulent (0).

## Modeling
The project employs various machine learning algorithms for fraud detection, including logistic regression, decision tree classifier, k-nearest neighbors (KNN), and random forest classifier. The modeling process involves training both vanilla and tuned versions of each algorithm to evaluate their performance and determine the most effective approach for fraud detection.

## Evaluation
Evaluation metrics such as cross-validation score, ROC AUC score, precision, recall, and F1-score are used to assess the models' performance. The evaluation process compares the effectiveness of different algorithms in accurately detecting fraudulent transactions while minimizing false positives and false negatives.

## Conclusion
The project concludes with insights into the effectiveness of different machine learning algorithms for fraud detection in credit card transactions. Recommendations are provided for further optimization and enhancement of the fraud detection model, ensuring robust protection against fraudulent activities in financial transactions.

## Acknowledgments

Contributors: 
- Joyleen Cherono
- Colins Wanjao
- Anita Bosibori
- Ruth Kamau 
- Benard Kinyua 
- Janet Atunga

Feel free to explore the code, provide feedback, or contribute for further enrichment. Happy modeling!
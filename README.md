# Credit Card and Bitcoin Fraud Management System

## Goal

This project, initiated during the final undergraduate year in collaboration with my peers, delves into the domain of Data Science and Machine Learning in the finance sector. Initially focusing on Credit Card Fraud Detection, the endeavor expanded to address the emerging challenges in Bitcoin fraud management, aiming to model supervised and unsupervised learning algorithms.

## Tech Stack

### Languages & Libraries
- Python, Numpy, Pandas, Matplotlib, Seaborn, Scikit-Learn, Jupyter Notebook

### Models Used
- Support Vector Machines, K-Nearest Neighbors, Artificial Neural Networks, Isolation Forest, Local Outlier Factor, K-Means Clustering

## Dataset

### Credit Card Dataset
The dataset contains transactions made by credit cards in September 2013 by European cardholders obtained from Kaggle. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

### BitCoin Dataset
Raw bitcoin blockchain data is used to create the dataset for this project. It consists of 3,02,48,134 transactions with 108 fraudulent transactions. The positive class (frauds) accounts for 0.00036% of all transactions. Each transaction can have multiple sender and receiver addresses, and each user remains anonymous as no personal information is associated with any addresses.

## Project

### Data Visualization, Manipulation & Feature Selection
- Visualized various features of the data for further analysis, such as usual transaction amounts in fraudulent and non-fraudulent transactions. 
- Implemented techniques like random resampling and univariate feature selection, optimizing feature sets for both datasets, strategically reducing computational costs, and augmenting model accuracy.

### Modeling Algorithms
- Leveraged supervised (K-Nearest Neighbors, Support Vector Machines, Artificial Neural Networks) and unsupervised (K-Means Clustering, Local Outlier Factor, Isolation Forest) learning algorithms.
- Criteria focused on handling outliers, non-linearities, and addressing challenges posed by imbalanced datasets.

### Evaluation Metrics
- Initially emphasized accuracy, shifting later to prioritize precision and recall due to dataset imbalance.
- Achieved commendable results, with an optimized F1 score of 91% using Artificial Neural Networks for credit card data and 57% using Support Vector Machines for Bitcoin data.

## Learnings and Improvements
- The inclusion of unsupervised machine learning algorithms provided insights into inherent data structures, aiding in potential fraud identification even in situations lacking labeled data.
- Understanding and implementing these techniques broadened the system's adaptability and robustness in real-world scenarios.
- Recognized the importance of precision and recall in imbalanced datasets.
- An avenue for future exploration involves hybrid classification techniques to enhance model performance, similar to a paper read on similar project that applied Naive Bayes to KNN resulting in increased precision, recall, and reduced model complexity. 

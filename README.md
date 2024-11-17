# Banking-Projects
Due to Non-Disclosure Agreements (NDA), real-world case studies cannot be shared. Instead, this document includes case studies based on synthetic data, designed to serve as a roadmap and guideline for new learners.
# Fraud Detection in Banking Systems

**Research Conducted by**  
**Mehdi Khaledi, Data Scientist, Nov 2024**

## Case Study Overview
This project focuses on developing a robust fraud detection system tailored to banking systems, addressing the growing complexity of financial transactions and fraud tactics. A synthetic dataset of 10,000 transactions, created to reflect real-world challenges, was used due to **NDA (Non-Disclosure Agreement)** constraints. The dataset presents a significant class imbalance, with fraudulent transactions forming a minority. The objective was to design a scalable machine learning solution that achieves high recall and precision, minimizing false positives and false negatives to balance fraud prevention and customer satisfaction.

## Approaches
Five machine learning approaches were explored to tackle the challenges of Fraud Detection in Banking Systems. Logistic Regression served as a baseline, while Random Forest and XGBoost demonstrated superior performance by handling non-linear patterns and class imbalance effectively. Support Vector Machines (SVM), optimized with PCA, aimed to address computational efficiency but struggled with imbalanced data. Neural Networks were implemented with dropout and L2 regularization, showing promise but facing overfitting and generalization issues.

## Results
XGBoost emerged as the most effective model, achieving the highest recall and minimizing false negatives, making it the preferred solution for fraud detection. Random Forest offered balanced performance with fewer false positives, serving as a reliable alternative. Metrics such as **precision**, **recall**, **F1-score**, and **AUC-ROC** were used to evaluate and compare the models, with a strong emphasis on minimizing false negatives to enhance fraud detection accuracy.

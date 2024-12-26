# Parkinson's Disease Prediction using Machine Learning

This project explores the application of **Machine Learning** techniques for predicting Parkinson's disease (PD). Parkinson's disease is a chronic and progressive neurodegenerative disorder that affects motor skills, leading to symptoms such as tremors, slowed movement, muscle rigidity, and postural instability. The objective of this project is to classify individuals into two categories: healthy individuals and individuals affected by Parkinson's disease, using various machine learning models.

---

## Project Overview

Parkinson's disease often shows early symptoms like tremors and rigidity, which worsen over time. Detecting these symptoms early can help in better management and treatment. This project uses **machine learning algorithms** to predict Parkinson's disease based on data collected from patients and healthy individuals. The study uses five machine learning models for classification: 

- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Random Forest (RF)**
- **Naive Bayes (NB)**
- **Decision Tree (DT)**

---

## Dataset

The dataset used in this study is sourced from the **UCI Machine Learning Repository** and consists of 188 PD patients and 64 healthy individuals. The data includes features extracted from sustained vowel phonation. These features were used to predict whether a person has Parkinson's disease or not. The dataset was split into **70% training data** and **30% test data** for model evaluation.

---

## Methodology

### Machine Learning Models Used:
1. **Random Forest (RF)**: An ensemble learning technique that uses multiple decision trees to improve prediction accuracy.
2. **Decision Tree (DT)**: A supervised learning technique that models data using a tree-like structure of decisions.
3. **Support Vector Machine (SVM)**: A powerful classifier that finds an optimal hyperplane to separate data into classes.
4. **Naive Bayes (NB)**: A probabilistic classifier based on Bayes' theorem, assuming feature independence.
5. **K-Nearest Neighbors (KNN)**: A non-parametric algorithm that classifies data based on the majority class of its nearest neighbors.

### Performance Metrics:
The models were evaluated based on several performance metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

---

## Results

The models were evaluated on their ability to predict Parkinson's disease, with the following results:

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| KNN   | 87.2%    | 85.5%     | 99.4%  | 91.9%    |
| SVM   | 83.7%    | 82.1%     | 99.4%  | 89.9%    |
| RF    | 85.9%    | 85.6%     | 96.9%  | 90.9%    |
| NB    | 76.6%    | 86.4%     | 80.7%  | 83.5%    |
| DT    | 76.2%    | 83.7%     | 83.7%  | 83.7%    |

- **KNN** achieved the highest accuracy (87.2%) and the best F1-score (91.9%).
- **SVM** and **KNN** performed equally well in recall (99.4%).
- **Naive Bayes (NB)** had the lowest accuracy (76.6%), but the highest precision (86.4%).

---

## Conclusion

This project demonstrates the application of machine learning algorithms to predict Parkinson’s disease based on speech features. The **K-Nearest Neighbors (KNN)** model outperformed others in terms of accuracy and F1-score, while **Support Vector Machine (SVM)** also showed high performance. The results highlight the potential of machine learning in clinical diagnosis and decision support systems for Parkinson's disease.

---

## Requirements

To run this project, you will need the following Python libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

---

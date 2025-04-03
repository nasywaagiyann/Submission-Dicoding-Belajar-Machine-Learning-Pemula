# 📌 Submission-Dicoding-Belajar-Machine-Learning-Pemula

## Project Overview
This project focuses on fraud detection using the Bank Transaction dataset sourced from Kaggle. It explores two key areas of Machine Learning: Clustering (Unsupervised Learning) and Classification (Supervised Learning).

## 🔍 Clustering (Unsupervised Learning)
- Utilized more than five features, including numerical and categorical data.
- Applied K-Means Clustering algorithm.
- Conducted feature selection to enhance clustering performance and compared results before and after selection.
- Determined the optimal number of clusters using the Silhouette Score, achieving 0.85.

## 📊 Classification (Supervised Learning)
After clustering, the cluster labels were transformed into target variables for classification. The following five classification models were implemented and evaluated:

| Model                          | Accuracy | Precision | Recall  | F1-Score |
|--------------------------------|----------|-----------|---------|----------|
| K-Nearest Neighbors (KNN)      | 98.61%   | 98.57%    | 98.76%  | 98.66%   |
| Decision Tree (DT)             | 100%     | 100%      | 100%    | 100%     |
| Random Forest (RF)             | 100%     | 100%      | 100%    | 100%     |
| Support Vector Machine (SVM)   | 100%     | 100%      | 100%    | 100%     |
| Naive Bayes (NB)               | 98.61%   | 98.35%    | 98.95%  | 98.61%   |

## 📂 Repository Structure
```
├── [Clustering]_Submission_Akhir_BMLP_Nasywa.ipynb  # Clustering Notebook
├── [Klasifikasi]_Submission_Akhir_BMLP_Nasywa.ipynb  # Classification Notebook
├── bank_transactions_data_2.csv  # Dataset
├── result_df.csv  # Result dataset
├── README.md  # Project documentation
```

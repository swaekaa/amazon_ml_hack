# Amazon ML Hackathon 🚀

This repository contains our end-to-end solution for the **Amazon Machine Learning Hackathon**.  
The project focuses on building a scalable and reproducible ML pipeline covering data preprocessing, model training, inference, and evaluation.

---

## 📌 Project Overview

The objective of this project is to solve a real-world machine learning problem using structured datasets and trained models.  
Key highlights include:

- Data cleaning, parsing, and feature engineering  
- Training and evaluation of ML models  
- Efficient handling of large datasets and models using **Git Large File Storage (LFS)**  
- Clean and reproducible workflow suitable for hackathons and production-grade ML projects  

---

## 🗂️ Repository Structure

```text
amazon_ml_hack/
│
├── data/                         # Datasets (tracked with Git LFS)
│   ├── train.csv
│   ├── test.csv
│   ├── parsed_train.csv
│   ├── parsed_test.csv
│   ├── train_processed.csv
│   ├── test_processed.csv
│   ├── train_with_predictions.csv
│   ├── submission.csv
│   └── output files
│
├── models/                       # Trained models (Git LFS)
│   ├── *.pkl
│   └── *.npy
│
├── notebooks/                    # Jupyter notebooks (EDA, training, experiments)
├── src/                          # Source code (preprocessing, training, inference)
├── README.md
└── LICENSE
```




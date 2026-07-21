# Airbnb Price Classification using Machine Learning

> End-to-end machine learning project comparing **Logistic Regression** and a **Neural Network** to classify Airbnb listings into high- and low-price categories.

![Business Brief](images/business-brief.png)

---

# Overview

This project was completed as part of the **Break Through Tech AI Machine Learning Foundations** program.

Working through a real-world business scenario, I developed and compared two supervised machine learning models to classify Airbnb listings into **high-price** and **low-price** categories based on listing characteristics.

The project demonstrates the complete machine learning lifecycle, including:

- Business Understanding
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Traditional Machine Learning
- Deep Learning
- Model Evaluation
- Business-Focused Recommendations

---

# Business Problem

### Company

**Trove Analytics**

### Role

**Junior Machine Learning Engineer**

Trove Analytics is developing a machine learning solution to help hospitality investment teams identify premium Airbnb listings more efficiently.

The objective was to build a binary classification model capable of predicting whether an Airbnb listing belongs to a **high-price** or **low-price** category based on listing characteristics such as:

- Location
- Room Type
- Host Characteristics
- Property Information
- Review Metrics

By automating this process, analysts can reduce manual review time, improve pricing consistency, and make more informed investment decisions.

---

# Machine Learning Workflow

- Business Understanding
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Missing Value Handling
- Feature Engineering
- One-Hot Encoding
- Train/Test Split
- Feature Scaling
- Logistic Regression
- Hyperparameter Tuning using GridSearchCV
- Neural Network (TensorFlow/Keras)
- Model Evaluation
- Business Recommendation

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Dataset

- **Dataset:** Airbnb NYC Listings
- **Records:** 28,000+ Listings
- **Problem Type:** Binary Classification
- **Target Variable:** Price Category (High vs. Low)

---

# Model Performance

| Model | Accuracy | F1 Score |
|-------|---------:|---------:|
| Logistic Regression | **81.1%** | **0.557** |
| Neural Network | **83.3%** | **0.621** |

![Model Results](images/model-results.png)

---

# Training Performance

## Training & Validation Loss

![Training Loss](images/training-loss.png)

The loss curves steadily decreased throughout training while validation loss remained stable, indicating that the model successfully learned meaningful patterns without significant overfitting.

---

## Training & Validation Accuracy

![Training Accuracy](images/training-accuracy.png)

Training and validation accuracy increased consistently throughout training, with only a small gap between the curves. This suggests the neural network converged effectively while maintaining good generalization performance.

---

# Key Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Feature Scaling
- Logistic Regression
- Hyperparameter Tuning
- GridSearchCV
- Neural Networks
- TensorFlow / Keras
- Binary Classification
- Model Evaluation
- Data Visualization
- Business Analytics

---

# Business Recommendation

The neural network achieved the strongest overall performance with an **accuracy of 83.3%** and an **F1 score of 0.621**, outperforming the logistic regression model on both evaluation metrics.

Although the neural network required additional training time and was less interpretable than logistic regression, its improved predictive performance justified the added complexity for this classification task.

---

# Future Improvements

Future enhancements could include:

- Evaluate Random Forest and XGBoost models.
- Address class imbalance using resampling techniques.
- Perform additional feature engineering.
- Deploy the model as an interactive web application.
- Evaluate model performance on unseen production data.

---

# Repository Structure

```text
airbnb-price-classification-ml/
│
├── Airbnb_Price_Classification.ipynb
├── Airbnb_Price_Classification_Capstone.ipynb
├── README.md
├── airbnbData_train.csv
├── airbnb_model.pkl
│
└── images/
    ├── business-brief.png
    ├── training-loss.png
    ├── training-accuracy.png
    └── model-results.png
```

---

# Learning Outcomes

This project strengthened my understanding of the complete machine learning lifecycle by applying traditional machine learning and deep learning techniques to a real-world business problem. It provided hands-on experience with exploratory data analysis, feature engineering, model optimization, neural networks, and communicating technical findings through business-focused recommendations.

---

# About

**Created by Maria Larson**

Completed through the **Break Through Tech AI Machine Learning Foundations** program.

This repository demonstrates an end-to-end machine learning workflow that compares traditional machine learning with deep learning to solve a real-world binary classification problem.

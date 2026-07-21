# 🏡 Airbnb Price Classification using Machine Learning

> **End-to-end machine learning project comparing Logistic Regression and Neural Networks to classify Airbnb listings into high- and low-price categories.**

![Business Brief](images/business-brief.jpeg)

---

# 📖 Overview

This project was completed through the **Break Through Tech AI Machine Learning Foundations** program.

Working as a **Junior Machine Learning Engineer** for **Trove Analytics**, I developed and compared two supervised machine learning models to classify Airbnb listings into **high-price** and **low-price** categories using listing characteristics.

The project demonstrates the complete machine learning lifecycle—from business understanding and exploratory data analysis to deep learning, model evaluation, and business recommendations.

---

# 💼 Business Problem

### Company
**Trove Analytics**

### Role
**Junior Machine Learning Engineer**

### Objective

Develop a machine learning model capable of predicting whether an Airbnb listing belongs to a **high-price** or **low-price** category.

### Business Value

- Reduce manual review time
- Improve pricing consistency
- Support hospitality investment decisions
- Identify premium listings more efficiently

---

# 🚀 Machine Learning Pipeline

```text
Business Understanding
        ↓
Exploratory Data Analysis (EDA)
        ↓
Data Cleaning & Preprocessing
        ↓
Feature Engineering
        ↓
Train/Test Split
        ↓
Feature Scaling
        ↓
Logistic Regression + GridSearchCV
        ↓
Neural Network (TensorFlow/Keras)
        ↓
Model Evaluation
        ↓
Business Recommendation
```

---

# 🛠 Technologies

| Programming | Machine Learning | Visualization |
|-------------|-----------------|---------------|
| Python | Scikit-learn | Matplotlib |
| Pandas | TensorFlow | Seaborn |
| NumPy | Keras | Jupyter Notebook |

---

# 📊 Dataset

| Attribute | Value |
|-----------|-------|
| Dataset | Airbnb NYC Listings |
| Records | 28,000+ |
| Problem Type | Binary Classification |
| Target Variable | Price Category (High vs. Low) |

---

# 📈 Model Performance

| Model | Accuracy | F1 Score |
|-------|---------:|---------:|
| Logistic Regression | **81.1%** | **0.557** |
| 🧠 Neural Network | **83.3%** | **0.621** |

![Model Results](images/model-results.jpeg)

---

# 📉 Training Performance

## Training & Validation Loss

![Training Loss](images/training-loss.jpeg)

The loss curves steadily decreased while validation loss remained stable, indicating that the neural network learned meaningful patterns without significant overfitting.

---

## 📈 Training & Validation Accuracy

![Training Accuracy](images/training-accuracy.jpeg)

Training and validation accuracy increased consistently throughout training with only a small gap between the curves, suggesting good generalization performance.

---

# 🎯 Key Skills Demonstrated

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Preprocessing
- ⚙️ Feature Engineering
- 📈 Feature Scaling
- 🤖 Logistic Regression
- 🔍 Hyperparameter Tuning (GridSearchCV)
- 🧠 Neural Networks
- ⚡ TensorFlow / Keras
- 📉 Model Evaluation
- 📊 Data Visualization
- 💼 Business Analytics

---

# 💡 Business Recommendation

The neural network achieved the strongest overall performance with an **accuracy of 83.3%** and an **F1 score of 0.621**.

Although it required additional training time and was less interpretable than Logistic Regression, its improved predictive performance justified the added complexity for this classification task.

---

# 🔮 Future Improvements

- Implement Random Forest and XGBoost models
- Address class imbalance through resampling techniques
- Experiment with additional feature engineering
- Deploy the model as a web application
- Evaluate performance on unseen production data

---

# 📂 Repository Structure

```text
airbnb-price-classification-ml/
│
├── Airbnb_Price_Classification_Capstone.ipynb
├── README.md
├── airbnbData_train.csv
├── airbnb_model.pkl
│
└── images/
    ├── business-brief.jpeg
    ├── training-loss.jpeg
    ├── training-accuracy.jpeg
    └── model-results.jpeg
```

---

# 🎓 Learning Outcomes

Through this project, I strengthened my understanding of:

- End-to-end machine learning workflows
- Data preprocessing and feature engineering
- Logistic Regression
- Neural Networks
- Hyperparameter tuning
- Model evaluation using Accuracy and F1 Score
- Translating technical findings into business recommendations

---

# 👩‍💻 About

**Maria Larson**

B.S. Data Science | Applied AI | Machine Learning | Product Analytics

Completed through the **Break Through Tech AI Machine Learning Foundations** program.

This repository showcases an end-to-end machine learning workflow that compares traditional machine learning with deep learning to solve a real-world binary classification problem.

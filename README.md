# 🔐 Password Strength Prediction System

A machine learning project designed to classify the strength of user passwords as weak, medium, or strong. This system leverages data preprocessing, feature engineering, and hyperparameter-tuned machine learning models to accurately assess password security.

---

## 📘 Description

This repository contains an end-to-end implementation of a Password Strength Prediction System using machine learning. The goal is to predict the strength of passwords and help users create more secure credentials.

---

## 🧠 What’s Inside

### 1. 🔍 Data Collection and Cleaning
- Loaded password datasets.
- Cleaned the data and handled missing/null values for robustness.

### 2. 🛠️ Data Preprocessing
- Extracted and created new features (e.g., length, character variety).
- Normalized and encoded necessary fields.

### 3. 📊 Data Visualization
- Performed Exploratory Data Analysis (EDA).
- Visualized character distributions and strength labels.

### 4. ⚙️ Feature Engineering
- Applied encoding techniques for categorical data.
- Selected the most relevant features for prediction.

### 5. 🤖 Model Building
- Built and trained a `RandomForestClassifier` to predict password strength.
- Evaluated model using metrics like accuracy, precision, recall, and F1-score.

### 6. 💾 Model Saving
- Used `pickle` to save the trained model for future inference.

### 7. 🔁 Automation
- Created a reusable function to automate model training and evaluation pipeline.

### 8. 🧪 Hyperparameter Tuning
- Used `GridSearchCV` to identify the best parameters for optimal model performance.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- pickle

### Installation

```bash
git clone https://github.com/yourusername/password-strength-predictor.git
cd password-strength-predictor
pip install -r requirements.txt
```

---

## 🧪 Usage

To train and test the model:

```python
from model import train_and_evaluate
train_and_evaluate()
```

To use the saved model for predictions:

```python
import pickle

model = pickle.load(open('password_strength_model.pkl', 'rb'))
prediction = model.predict([your_feature_vector])
```

---

## 📈 Results

- Achieved high accuracy and generalization on unseen password data.
- Successfully classified passwords into multiple strength categories.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repository and submit a pull request.

---

**Note:** Always encourage users to use password managers and follow best security practices. This tool is for educational and research purposes.


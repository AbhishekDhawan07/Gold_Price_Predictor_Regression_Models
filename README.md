# 🪙 Gold Price Predictor using Regression Models

A Machine Learning project focused on predicting **Gold Prices** using multiple regression algorithms and comparing their performance.

This project demonstrates how different models perform on the same dataset using **R² Score evaluation**.

---

## 📋 Contents

- Project Overview  
- Models Used  
- Technologies Used  
- Project Structure  
- Model Performance Comparison  
- Insights  
- Important Observation  
- How to Run  
- Objectives  
- Future Improvements  
- Contributing  

---

## 📌 Project Overview

This project applies multiple regression models to predict gold prices and compares their performance using:

- Training R² Score  
- Testing R² Score  

---

## 🧠 Models Used

- 🌲 Random Forest Regressor (RFR)  
- 🌳 Decision Tree Regressor (DTR)  
- 📈 Support Vector Regressor (SVR)  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📂 Project Structure
```
Gold_Price_Predictor_Regression_Models/
│
├── Different ML Models Project - Gold Price Prediction/
│ ├── gold_price_prediction.ipynb
│ ├── dataset.csv
│
├── training_r2.png
├── testing_r2.png
│
└── README.md
```

---

## 📊 Model Performance Comparison

### 🔹 Training R² Score Comparison

![Training R2 Score](training_r2.png)

---

### 🔹 Testing R² Score Comparison

![Testing R2 Score](testing_r2.png)

---

## 📈 Insights

- **Decision Tree Regressor (DTR)** shows the highest performance on both training and testing data  
- **Random Forest Regressor (RFR)** also performs very well with slightly lower scores than DTR  
- **Support Vector Regressor (SVR)** performs comparatively lower than tree-based models  

---

## ⚠️ Important Observation

- Very high R² scores (~0.98–1.0) may indicate:
  - Possible **overfitting**, especially for Decision Tree  
  - Need for **cross-validation** and tuning  

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib scikit-learn
jupyter notebook
```
---

## 📌 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Feature Engineering
- Add more regression models

---

🤝 Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request 🚀

---

> ⭐ If you found this project useful, consider starring the repository!


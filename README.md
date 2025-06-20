# 🚦 Accident Severity Prediction using Machine Learning (KNN) 

This project applies machine learning techniques to predict the severity of road traffic accidents using real-world data collected from police records in Addis Ababa (2017–2020). By leveraging classification algorithms and data preprocessing techniques, it aims to support proactive safety measures and smarter resource planning.

## 📊 Dataset Overview
- **Instances**: 12,316
- **Features**: 32 (including 8 categorical)

## 🎯 Project Objectives
- Predict accident severity based on environmental and contextual factors.
- Improve model interpretability and prediction accuracy.
- Identify key variables influencing accident outcomes.

## 🧰 Tools & Techniques
- **Programming Language**: Python (Jupyter Notebook)
- **Libraries Used**: pandas, numpy, seaborn, matplotlib, sklearn
- **ML Algorithm**: K-Nearest Neighbors (K-NN)
- **Preprocessing**:
  - Label Encoding of categorical variables
  - Feature selection via variance and correlation
  - Handling missing values with `dropna`
- **Evaluation Metrics**: Accuracy (83%), Confusion Matrix, Precision, Recall, F1-Score

## 🔍 Key Insights
- K-NN model performed best at a 20% test split with fine-tuned K-values.
- Label encoding and variable reduction significantly improved accuracy.
- The project provides a replicable framework for predictive safety modeling.

## 💡 Impact
The model achieved **83% accuracy**, offering a reliable tool for predicting accident severity and informing public safety decisions. It demonstrates how machine learning can be applied to real-world problems for impactful outcomes.

---

**Disclaimer**: Dataset and findings are for educational purposes and should be evaluated before operational use.

# Data_Analysis_Project

# Advanced Data Analysis & Machine Learning Project

## 📌 Project Overview
This project performs **data analysis, visualization, and classification modeling** using **Support Vector Classification (SVC) with hyperparameter tuning** and **Random Forest Classifier**. It includes:

- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Data Visualization (Heatmaps, Scatter Plots, Boxplots, Histograms)**
- **Machine Learning Models (SVC & Random Forest)**
- **Hyperparameter Tuning using GridSearchCV**
- **Model Evaluation with Accuracy, Classification Report, and Confusion Matrix**
- **Model Saving for Future Use**

---

## 📂 Files Included
- **`data_analysis_project.py`** - Main Python script for analysis, visualization, and model training.
- **`data.csv`** - Placeholder dataset (replace with your actual data).
- **`best_svc_model.pkl`** - Trained Support Vector Classifier model.
- **`random_forest_model.pkl`** - Trained Random Forest Classifier model.
- **`README.md`** - Project documentation.

---

## 🚀 How to Run the Project

### **1️⃣ Install Dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### **2️⃣ Run the Script**
```bash
python data_analysis_project.py
```

---

## 📊 Data Visualization & Insights
The script generates the following plots to understand the dataset:
- **Correlation Heatmap** 📈
- **Histograms** 📊
- **Boxplots for Outlier Detection** 📦
- **Scatter Plots for Feature Relationships** 🔎

---

## 🤖 Machine Learning Models
### **1️⃣ Support Vector Classifier (SVC) with Hyperparameter Tuning**
- Uses **GridSearchCV** to find the best hyperparameters.
- **Linear & RBF kernels** are evaluated.
- Best model is saved as `best_svc_model.pkl`.

### **2️⃣ Random Forest Classifier**
- Trained alongside SVC for comparison.
- Uses **100 decision trees** for classification.
- Model is saved as `random_forest_model.pkl`.

---

## 📈 Model Evaluation
The script evaluates models using:
✅ **Accuracy Score**
✅ **Classification Report** (Precision, Recall, F1-score)
✅ **Confusion Matrix**

---

## 📥 Contributing
Feel free to **fork** this repository, improve it, and submit a **pull request**. Suggestions & improvements are welcome! 🚀

---

## 🏆 Acknowledgments
This project is part of my **Data Science & Machine Learning journey** to improve my skills in data analysis, visualization, and model building.

🌟 **If you like this project, give it a ⭐ on GitHub!** 🌟


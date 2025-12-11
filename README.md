# 🩺 Medical Insurance Premium Prediction Using Machine Learning

This project focuses on predicting **medical insurance premiums** using Machine Learning techniques. By analyzing demographic and health-related factors such as age, BMI, smoking habits, number of children, sex, and region, the model estimates insurance charges with high accuracy. The project demonstrates a complete ML pipeline including EDA, preprocessing, model building, evaluation, and prediction.

---

## 📊 Project Overview

The dataset contains **1338 samples** and 7 attributes. After detailed analysis and feature engineering, multiple ML models were trained. Among them, **XGBoost Regressor** achieved the best performance.

This project helps understand how personal habits and health indicators influence medical insurance pricing.

---

## 📂 Features Used

- **Age**
- **Sex**
- **BMI**
- **Children**
- **Smoker**
- **Region**
- **Charges** (Target variable)

---

## 🔍 Exploratory Data Analysis (EDA)

Insights discovered:

- **Smokers pay drastically higher premiums** than non-smokers.
- **BMI** shows a strong positive relationship with insurance charges.
- **Age** contributes significantly to increased premiums.
- Region has minor but notable effects.
- Lifestyle and health impact insurance cost directly.

Visualizations included:
- Distribution plots  
- Pair plots  
- Heatmaps  
- Categorical comparisons  

---

## 🛠️ Machine Learning Workflow

### **1. Data Preprocessing**
- Handling missing data (if any)
- Mapping categorical variables (sex, smoker)
- One-hot encoding (region)
- Splitting data into train/test sets
- Scaling numeric features using `StandardScaler`

### **2. Models Implemented**
- Linear Regression  
- Lasso Regression  
- Ridge Regression  
- Random Forest Regressor  
- **XGBoost Regressor (Best Performer)**  

### **3. Model Evaluation Metrics**
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

XGBoost consistently produced the lowest error.

---

## 🧮 Final Prediction System

A complete prediction pipeline was implemented that:

1. Accepts user input values  
2. Converts categorical data  
3. Scales numeric fields  
4. Predicts medical insurance premium using the trained XGBoost model  

This makes the system ready for deployment in real-time applications.

---

## 🚀 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- XGBoost  

---

## 📦 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/yourusername/medical-insurance-premium-prediction.git

# Move into the folder
cd medical-insurance-premium-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook

```

## 🚀 Future Enhancements

- Add medical history features (BP, cholesterol, diseases)
- Hyperparameter tuning for XGBoost
- Deploy using Streamlit or Flask
- Add model explainability (LIME, SHAP)
- Cloud deployment (AWS / GCP / Render)
- Build an insurance recommendation engine

---

## ⚠️ Limitations

- Dataset is relatively small (1338 samples)
- Limited features reduce real-world accuracy
- No actual medical test data included
- Model may be biased due to class imbalance (smokers)

---

## 🏁 Conclusion

This project demonstrates how machine learning can effectively predict medical insurance premiums and uncover the key factors affecting them. With XGBoost as the final model, the system achieves strong accuracy and provides meaningful insights into insurance pricing. The project can be further expanded into a full-fledged application for insurance companies or customers.

---

## 🤝 Contributions

Contributions, feature requests, and issues are welcome.

---

## 🧑‍💻 Author

**Kandula Lohith Chandra Varma**  
Machine Learning & Data Science Enthusiast  
GitHub: *Chandravarma2004*  
LinkedIn: *www.linkedin.com/in/lohith-chandra-varma-kandula*  

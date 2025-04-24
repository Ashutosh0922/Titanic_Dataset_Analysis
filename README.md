# Titanic_Dataset_Analysis

# 🚢 Titanic Dataset Preprocessing Project

This project is focused on **data cleaning, preprocessing, and outlier handling** using the popular **Titanic dataset** from Kaggle. It is designed to build foundational data handling skills that are crucial for any machine learning workflow.



## 📌 Project Objectives

- Clean raw data and handle missing values.
- Encode categorical features into numerical formats.
- Normalize/standardize numerical features.
- Visualize and remove outliers.
- Prepare the dataset for further ML model training.



## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for encoding & scaling)



## 🧪 Steps Performed

1. **Dataset Loading & Exploration**  
   - Loaded the Titanic dataset using `pandas`  
   - Checked for null values and data types

2. **Missing Value Handling**  
   - Filled missing values in `Age` using median  
   - Filled missing values in `Embarked` using mode

3. **Encoding Categorical Variables**  
   - Applied `LabelEncoder` to convert `Sex` and `Embarked` to numeric

4. **Feature Scaling**  
   - Standardized `Age` and `Fare` using `StandardScaler`

5. **Outlier Detection and Removal**  
   - Plotted boxplots for `Age` and `Fare`  
   - Removed outliers beyond the 99th percentile threshold



## 📁 Files

- `Titanic_Dataset_Analysis.ipynb` - Jupyter notebook with complete preprocessing code
- `titanic.csv` - The raw dataset (not included in this repo; assumed to be added manually)
- `README.md` - Project documentation



## 📈 Future Scope

This cleaned and preprocessed dataset can now be used for:
- Classification models (e.g., Random Forest, Logistic Regression)
- Survival prediction applications
- ML deployment projects


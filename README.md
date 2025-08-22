# 🏠 House Price Prediction

## 📌 Project Overview
This project predicts **house prices** using machine learning.  
Given features of a house (e.g., size, location, number of rooms, year built), the model estimates its **market price**.  

This is a **supervised regression problem**, where the target variable is the **price** column from the dataset.

---

## 📂 Project Structure
- `Housing_data.csv` → dataset
- `House_Price_Prediction_Filled.ipynb` → Jupyter notebook with code
- `README.md` → project description
- `report.pdf` (optional) → detailed report of findings

---

## ⚙️ Steps in the Notebook
1. **Import libraries** (pandas, numpy, matplotlib, seaborn, scikit-learn)  
2. **Load dataset** → inspect shape, types, missing values  
3. **Exploratory Data Analysis (EDA)** → distributions, correlations, heatmaps, pairplots  
4. **Preprocessing**  
   - Handle missing values  
   - Encode categorical features  
   - Scale numeric features  
5. **Model Training**  
   - Train/test split (80/20)  
   - Linear Regression model  
6. **Evaluation**  
   - Metrics: Mean Squared Error (MSE), R² score  
   - Visualization: Predicted vs Actual Prices  

---

## 📊 Results
- The model explains a significant portion of house price variance (R² score).  
- Key attributes influencing price:  
  - **Square footage** → strong positive correlation with price  
  - **Location** → some neighborhoods increase/decrease house values  
  - **Number of rooms** → positive, but diminishing returns  
  - **Year built** → newer houses often priced higher  

---

## 🚀 Future Improvements
- Try **advanced models**: Random Forest, Gradient Boosting, XGBoost  
- Perform **feature engineering** (e.g., price per square foot, age of house)  
- Hyperparameter tuning for better accuracy  

---

## 🛠️ Requirements
Install dependencies via:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

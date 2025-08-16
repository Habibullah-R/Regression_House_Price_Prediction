# 🏠 House Price Prediction - Regression Model

A machine learning project to predict house prices using regression techniques.  
The notebook explores different models and identifies the best-performing one for this dataset.

---

## 📖 Project Overview
This project demonstrates:
- Data preprocessing (handling missing values, scaling, encoding)
- Exploratory Data Analysis (EDA) with visualizations
- Model training and evaluation using regression algorithms
- Comparison of Linear Regression, Random Forest, and XGBoost
- Final prediction using the best model (Linear Regression)

---

## 📂 Project Structure
```
├── Regression_House_price_Prediction.ipynb 
├── house price (train).csv 
├── house price test.csv 
├── requirements.txt 
└── README.md
```



---

## 📊 Dataset
- **Name**: House Price Dataset  
- **Source**: (Add Kaggle/UCI link if public)  
- **Target variable**: `SalePrice`  
- **Features**: Various numerical and categorical attributes related to houses (e.g., area, quality, year built).

---

## 🧠 Models Used
- Linear Regression ✅ (Best performance)
- Random Forest Regressor
- XGBoost Regressor

**Evaluation Metrics:**
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

---

## 📈 Results
- **Best Model**: Linear Regression  
- **Notes**: SalePrice distribution was log-transformed for normalization  
- **Performance**: (Insert your actual MSE, MAE, R² values here)

---

## 🚀 How to Run

### Run in Google Colab
Open and run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/drive/1KyMjMc0_CUq270NRkBOt4mcV_4_o1Qgd?usp=sharing)](YOUR_COLAB_NOTEBOOK_LINK)

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo

2. Install dependencies:
   pip install -r requirements.txt

3. Open the notebook:
   jupyter notebook Regression_House_price_Prediction.ipynb

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.


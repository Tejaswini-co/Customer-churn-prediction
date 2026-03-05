# Customer Churn Prediction - Data Science Project

## 📊 Project Overview

This is a comprehensive end-to-end data science project that predicts customer churn for a telecommunications company using the Telco Customer Churn dataset. The project demonstrates the complete machine learning workflow from business understanding to actionable recommendations.

## 🎯 Business Objective

Build a predictive model to identify customers at high risk of churning, enabling proactive retention strategies and reducing customer acquisition costs.

## 📁 Project Structure

```
CUSTOMER CHURN PREDICTION/
│
├── customer_churn_analysis.ipynb    # Main Jupyter notebook with complete analysis
├── Telco-Customer-Churn.csv         # Dataset (automatically downloaded)
├── requirements.txt                 # Python dependencies
├── Medium_Article.md                # Complete Medium article overview
├── README.md                         # Project documentation
├── screenshots/                     # Screenshots and visualization guide
└── .venv/                           # Virtual environment (created during setup)
```

## 📖 Medium Article & Documentation

A comprehensive Medium article is included (`Medium_Article.md`) that provides:
- **Complete project walkthrough** with business context
- **Technical implementation details**
- **Key insights and visualizations**
- **Business recommendations**
- **Model performance analysis**

### Adding Screenshots
The `screenshots/` folder contains instructions for creating professional screenshots:
- Churn distribution charts
- Feature importance plots
- Model comparison visualizations
- ROC curves and confusion matrices

**To create screenshots:**
1. Run the Jupyter notebook completely
2. Use Windows Snip & Sketch (Win + Shift + S) to capture plots
3. Save as PNG files in the `screenshots/` folder
4. Upload to Medium when publishing the article

## 🛠️ Setup Instructions

### Prerequisites
- Python 3.9 or higher
- VS Code with Jupyter extension (recommended)

### 1. Clone/Download the Project
```bash
# If cloning from repository
git clone <repository-url>
cd CUSTOMER\ CHURN\ PREDICTION
```

### 2. Set Up Virtual Environment
```bash
# Create virtual environment
python -m venv .venv

# Activate virtual environment
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
# source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

Or open `customer_churn_analysis.ipynb` directly in VS Code.

## 🛠️ Technologies Used

- **Python 3.9+**
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
  - Logistic Regression
  - Decision Tree
  - Random Forest

## 📋 Project Sections

### 1. Business Understanding
- Explanation of customer churn and its business impact
- Project objectives and success metrics

### 2. Data Cleaning
- Handle missing values
- Convert data types (TotalCharges to numeric)
- Remove duplicates
- Drop unnecessary columns

### 3. Exploratory Data Analysis (EDA)
- Univariate analysis of numerical and categorical features
- Bivariate analysis (Churn vs features)
- Correlation heatmap
- Business insights from visualizations

### 4. Feature Engineering
- Create tenure groups (New, Mid-term, Long-term, Very Long-term)
- Derive meaningful features
- Business justification for new features

### 5. Data Preprocessing
- Encode categorical variables (Label Encoding & One-Hot Encoding)
- Train-test split (80/20)
- Feature scaling (StandardScaler)

### 6. Model Building
- Logistic Regression
- Decision Tree
- Random Forest

### 7. Model Evaluation
- Performance metrics (Accuracy, Precision, Recall, F1-Score)
- Confusion matrices
- ROC curves and AUC scores
- Comprehensive model comparison table

### 8. Feature Importance Analysis
- Top features driving churn
- Business interpretation of important features

### 9. Business Recommendations
- 7 actionable strategies to reduce churn
- Expected outcomes and ROI

## 📊 Key Findings

- **Tenure** is the strongest predictor of churn (new customers at highest risk)
- **Monthly charges** show strong correlation with churn
- **Month-to-month contracts** have significantly higher churn rates
- **Electronic check** payment method users churn more
- Models achieve 75-80% accuracy with good recall rates

## 🎯 Business Impact

Expected outcomes from implementing recommendations:
- 20-30% reduction in churn rate within 12 months
- Increased customer lifetime value (CLV)
- Improved customer satisfaction
- Better resource allocation for retention efforts

## 🚀 How to Run

1. **Install Required Libraries**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. **Open the Notebook**:
   - Open `customer_churn_analysis.ipynb` in Jupyter Notebook or VS Code
   - Run cells sequentially

3. **Dataset**:
   - The notebook loads data directly from GitHub URL
   - Alternatively, download from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 📈 Model Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score | AUC |
|-------|----------|-----------|--------|----------|-----|
| Logistic Regression | ~80% | ~66% | ~55% | ~60% | ~0.85 |
| Decision Tree | ~73% | ~49% | ~53% | ~51% | ~0.72 |
| Random Forest | ~79% | ~64% | ~48% | ~55% | ~0.83 |

*Note: Exact metrics may vary based on data*

## 🎓 Skills Demonstrated

- ✅ Business problem formulation
- ✅ Exploratory Data Analysis (EDA)
- ✅ Data cleaning and preprocessing
- ✅ Feature engineering
- ✅ Multiple ML algorithms
- ✅ Model evaluation and comparison
- ✅ Data visualization
- ✅ Business insights and recommendations
- ✅ Clear documentation

## 👤 Author

Data Science Portfolio Project  
March 2026

## 📝 License

This project is for educational and portfolio purposes.

---

**Portfolio-Ready for Data Analyst/Data Science Internship Applications** 🎯

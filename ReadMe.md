# Laptop Price Analysis

A data science project analyzing laptop pricing factors and building predictive models using Python and machine learning techniques.

## 📊 Project Overview

This project performs comprehensive analysis on laptop pricing data, including data cleaning, exploratory analysis, feature engineering, and machine learning model development to predict laptop prices based on various specifications.

## 🎯 Objectives

- Clean and preprocess laptop dataset
- Handle missing values and fix data types
- Standardize measurements and normalize features
- Create meaningful features through binning and encoding
- Build and evaluate regression models
- Optimize model performance using Ridge Regression and Grid Search
- Identify overfitting and apply regularization techniques

## 📁 Project Files

```
laptop-price-analysis/
│
├── README.md                 # Project documentation
├── laptopanalysis.ipynb      # Complete analysis notebook
├── laptops.csv               # Dataset (238 laptop entries)
```

## 🔧 Technologies Used

- **Python 3.13+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning models and evaluation
- **Jupyter Notebook** - Interactive development environment

## 📈 Analysis Workflow

### 1. Data Wrangling
- **Missing Data Handling**
  - Imputed continuous variables (Weight) using mean
  - Imputed categorical variables (Screen Size) using mode
- **Data Type Corrections**
  - Converted object types to float for numerical operations
- **Standardization**
  - Weight: kg → pounds
  - Screen Size: cm → inches
- **Normalization**
  - CPU frequency scaled to [0, 1] range
- **Feature Engineering**
  - Created price bins (Low, Medium, High)
  - Generated indicator variables for categorical features

### 2. Model Development & Evaluation
- **Linear Regression** - Baseline model
- **Cross-Validation** - 4-fold validation for robust evaluation
- **Polynomial Features** - Testing degrees 1-5 to identify overfitting
- **Ridge Regression** - Regularization to prevent overfitting
- **Grid Search** - Hyperparameter optimization for best alpha value

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.13 or higher
pip package manager
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/laptop-price-analysis.git
cd laptop-price-analysis
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook laptopanalysis.ipynb
```

4. **Run all cells** to execute the complete analysis

## 📊 Dataset Features

The dataset contains **238 laptop entries** with the following attributes:

| Feature | Description | Type |
|---------|-------------|------|
| Manufacturer | Laptop brand | Categorical |
| Category | Laptop type (Gaming, Business, etc.) | Categorical |
| Screen | Display type (IPS Panel, Full HD) | Categorical |
| CPU_frequency | Processor speed (GHz) | Continuous |
| RAM_GB | Memory size (GB) | Continuous |
| Storage_GB_SSD | SSD storage capacity (GB) | Continuous |
| CPU_core | Number of processor cores | Discrete |
| OS | Operating system | Categorical |
| GPU | Graphics card | Categorical |
| Weight_kg | Laptop weight (kg) | Continuous |
| Screen_Size_cm | Display size (cm) | Continuous |
| **Price** | **Target variable ($)** | **Continuous** |

## 🔍 Key Findings

- Successfully handled missing data in Weight and Screen Size columns
- Identified optimal polynomial degree to avoid overfitting
- Ridge Regression improved model performance through regularization
- Grid Search identified the best hyperparameters for the model
- Created visualizations showing relationships between features and price

## 📉 Visualizations

The notebook includes:
- Missing data heatmaps
- Price distribution by category
- Feature vs Price scatter plots
- Overfitting analysis (R² vs Polynomial Degree)
- Regularization impact (R² vs Alpha parameter)
- Price distribution histogram with statistical measures

## 🎓 Skills Demonstrated

- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Statistical Analysis**
- **Machine Learning Model Development**
- **Model Evaluation & Validation**
- **Hyperparameter Tuning**
- **Data Visualization**
- **Python Programming**

## 📝 Results Summary

- Cleaned dataset with zero missing values
- Identified key pricing factors
- Built optimized regression model
- Evaluated model performance using multiple metrics
- Prevented overfitting through cross-validation and regularization

## 🔮 Future Enhancements

- [ ] Implement advanced models (Random Forest, XGBoost, Neural Networks)
- [ ] Feature importance analysis
- [ ] Interactive dashboard using Streamlit or Plotly Dash
- [ ] Deploy model as REST API using Flask/FastAPI
- [ ] Add real-time price prediction functionality
- [ ] Expand dataset with more laptop entries
- [ ] A/B testing different model architectures

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👩‍💻 Author

**Sakshi Goel**

- GitHub: https://github.com/GoelSakshi742
- LinkedIn: https://www.linkedin.com/in/sakshi742/
- Email: ersakshigoel@gmail.com

## 🙏 Acknowledgments

- Dataset and problem framework inspired by IBM Data Analysis course
- All code implementation, analysis, and insights are original work
- Thanks to the open-source community for excellent Python libraries

---

### 📌 Project Status

✅ **Completed** - Ready for portfolio showcase

---

⭐ **If you find this project helpful, please give it a star!**

💬 **Questions or suggestions?** Feel free to open an issue or reach out!
# 💻 Laptop Price Analysis & Machine Learning

Predicting laptop prices using **Ridge Regression** and **hyperparameter tuning** to build robust machine learning models.

***

## 📊 Overview
This project analyzes laptop specifications and pricing data to evaluate model performance, prevent overfitting, and optimize regression parameters for better accuracy.

***

## ⚙️ Tools & Techniques
- Python (3.13+), Pandas, NumPy  
- Scikit-learn (LinearRegression, Ridge, GridSearchCV)  
- Matplotlib, Seaborn, tqdm, Jupyter Notebook  

***

## 🚀 Highlights
- Tested 90/10 and 50/50 splits  
- Polynomial feature expansion (degree 1–5)  
- Ridge Regression (α range 0.001–1.000)  
- Grid Search: best α = 10 → Test R² = 0.301, Train R² = 0.669  

***

## 🧠 Insights
- Single-feature models underfit (R² = -0.066)  
- Polynomial features improved complexity  
- Regularization reduced overfitting  
- Ridge (α = 10) gave best generalization  

***

## 📈 Results Summary

| Model | Train R² | Test R² |
|--------|-----------|----------|
| Linear Regression | — | -0.066 |
| Ridge Regression | 0.669 | 0.423 |
| Grid Search Ridge | — | 0.301 |

***

## 📂 Dataset
238 laptops, including attributes like CPU, RAM, Storage, OS, GPU, Category, Screen, and **Price (target variable)**.

***

## 🔮 Next Steps
- Add Random Forest & XGBoost  
- Apply advanced feature engineering  
- Deploy final model via REST API  

***

## 👩‍💻 Author
**Sakshi Goel**  
[GitHub](https://github.com/GoelSakshi742) -  [LinkedIn](https://www.linkedin.com/in/sakshi742/) -  [Email](mailto:ersakshigoel@gmail.com)

***

## 🙏 Acknowledgments
Inspired by the IBM Data Analysis course.  
Model design, evaluation, and optimization are original work.

***

✅ **Status:** Completed — Ready for deployment.  
⭐ *If this project helped you, please star the repo!*

***

☕ Coffee Shop Revenue Analysis and Modeling

A data-driven project analyzing and modeling the factors influencing daily revenue in a coffee shop using Exploratory Data Analysis (EDA) and multiple machine learning regression techniques.

📘 Overview

This project investigates how key business metrics — including customer count, average order value, marketing spend, and foot traffic — influence a coffee shop’s daily revenue.

Using a combination of data visualization, statistical assumption testing, and regression modeling, the study identifies the most significant predictors of revenue and evaluates several machine learning models to determine the best fit.

🎯 Objectives

Perform exploratory data analysis (EDA) to understand relationships between features

Test linear regression assumptions to ensure model validity

Build and compare multiple regression models

Evaluate model accuracy using R², RMSE, and MAPE

Visualize and interpret actual vs. predicted revenue trends

🧩 Project Workflow
1️⃣ Exploratory Data Analysis (EDA)

Displayed data structure and statistical summary

Plotted correlation heatmap, distribution plots, and pairplots

Identified outliers and key drivers affecting revenue

Analyzed average revenue across locations

2️⃣ Linear Regression Assumption Testing

Before training, all major assumptions were checked:

✅ Linearity

✅ Homoscedasticity

✅ Normality of residuals

✅ Independence of errors

✅ No multicollinearity


3️⃣ Model Development and Evaluation

Built and compared multiple regression algorithms to identify the most accurate model.

🏆 Best Model:
Polynomial Regression (Degree = 2) achieved the best overall performance with R² ≈ 0.96 and MAPE ≈ 12.3 %.

📈 Visualizations

1️⃣ Correlation Heatmap: Reveals strong relationships between customers, average_order_value, and revenue.

2️⃣ Revenue Distribution: Shows overall sales spread and skewness.

3️⃣ Outlier Analysis:Boxplots identified high-marketing-spend outliers.

4️⃣ Feature Relationships: Pairplots illustrated how revenue varies with core variables.

5️⃣ Actual vs Predicted (Polynomial Regression): The red dashed line represents perfect prediction alignment.

⚙️ Installation & Setup

Clone the Repository

git clone https://github.com/<your-username>/coffee-shop-revenue-analysis.git

cd coffee-shop-revenue-analysis

Create a Virtual Environment:

python -m venv venv


Activate it:

Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate

Install Dependencies
pip install -r requirements.txt

If not available:

pip install pandas numpy matplotlib seaborn scikit-learn

🚀 How to Run

Launch the notebook:

jupyter notebook main.ipynb


This will:

Load the dataset

Perform data analysis & visualization

Test regression assumptions

Train and evaluate models

Display the comparison table and plots

💡 Insights & Takeaways

Polynomial Regression achieved the highest accuracy and lowest prediction error.

Customer count, average order value, and marketing spend are the strongest predictors of revenue.

Ensemble models (Random Forest, Gradient Boosting) perform well but require higher computational cost.

The coffee shop’s revenue pattern follows a non-linear relationship with key operational factors.


🔮 Future Enhancements

Automate hyperparameter tuning using GridSearchCV

Build a Streamlit dashboard for interactive revenue analysis

Integrate time-series components for seasonality tracking

Add model explainability with SHAP or LIME


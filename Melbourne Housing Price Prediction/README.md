🏡 Melbourne Housing Price Prediction
This project predicts housing prices in Melbourne using machine learning regression models. It aims to assist stakeholders such as real estate agencies, buyers, and investors in making data-driven decisions by estimating house prices based on various features like location, land size, number of rooms, and more.

📁 Project Structure
melbourne_housing_price_prediction/
│
├── melbourne_housing.ipynb       # Main Jupyter Notebook
├── melbourne_housing.csv         # Dataset (from Kaggle or official source)
├── requirements.txt              # Required libraries
└── README.md                     # Project description


📊 Problem Statement
The Melbourne real estate market is dynamic and influenced by multiple factors. Predicting house prices helps:

Buyers understand fair pricing

Sellers decide listing prices

Investors make profitable choices

Our goal is to develop a robust regression model that accurately estimates house prices using historical housing data.


🔍 Data Overview
Source: Kaggle - Melbourne Housing Dataset

Features include:

Suburb, Address, Rooms, Type, Price, Distance to CBD, Bedroom2, Bathroom, Car, Landsize, BuildingArea, YearBuilt, CouncilArea, Regionname, etc.


⚙️ Technologies Used
Python 🐍

NumPy & Pandas (data manipulation)

Matplotlib & Seaborn (data visualization)

Scikit-learn (modeling & evaluation)

XGBoost (advanced boosting model)

Jupyter Notebook


🧹 Data Cleaning

Dropped columns with excessive missing values

Imputed or removed rows with nulls

Converted categorical features using encoding

Removed outliers for better model generalization


🤖 Models Trained

Linear Regression

Ridge & Lasso Regression

Random Forest Regressor

XGBoost Regressor

📈 Evaluation Metrics
R² Score

Adjusted R²

RMSE (Root Mean Squared Error)
Best performance achieved with XGBoost model:


💡 Key Insights
Location and land size are the most influential features.

Boosting models outperform linear models on non-linear data.

Data preprocessing significantly impacts model accuracy.


📝 How to Run
Clone the repository:

git clone https://github.com/kanmeet/Machine-Learning-Model.git
cd Machine-Learning-Model

Install dependencies:
pip install -r requirements.txt


Open and run the notebook:
jupyter notebook melbourne_housing.ipynb

📌 Recommendations
Gather newer data to reflect post-COVID price trends.

Include geospatial and economic indicators for improved performance.

Deploy model using a web app (e.g., Streamlit or Flask) for real-time predictions.


🙋‍♀️ Author
Anmeet Kaur
📧 Email | 🔗 GitHub | Machine Learning



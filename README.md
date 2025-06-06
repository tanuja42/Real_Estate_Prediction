🏙️ Bengaluru Real Estate Price Prediction
This project uses Machine Learning techniques to predict real estate property prices in Bengaluru based on various features like location, size, number of bedrooms, square footage, and more. The model is trained using a cleaned and processed dataset, and implements regression models to provide accurate and useful predictions.

📌 Project Overview
Objective: Predict house prices in Bengaluru using supervised learning.
Language: Python
Platform: Jupyter Notebook
Dataset: Bengaluru house price dataset (CSV format)
ML Algorithm Used: Linear Regression (with experimentation using Lasso and Decision Tree Regressor via GridSearchCV).

🔍 Features Used for Prediction
Location
Square Foot Area (total_sqft)
Number of Bedrooms (BHK)
Number of Bathrooms
Price per square foot (price_per_sqft)

🧹 Data Cleaning & Preprocessing
The dataset contains inconsistencies like:
Irregular formats in square footage
Non-numeric entries
Missing values
Steps taken:
Extracted numerical values from ranges and strings
Handled missing/null values
Removed outliers using standard deviation and domain logic
One-hot encoding of categorical variables (like location)

🧠 Model Building
Models Tried:
Linear Regression: Final selected model
Lasso Regression: Regularized model tested via GridSearchCV
Decision Tree Regressor: Also tested using GridSearchCV
Model Selection:
Used cross-validation and GridSearchCV to tune hyperparameters and select the best model.

🖥️ How to Run
Clone this repository:
git clone https://github.com/your-username/bengaluru-real-estate-price-prediction.git
cd bengaluru-real-estate-price-prediction
Install dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook:
jupyter notebook bhp.ipynb

The model allows prediction of real estate prices given the following input:
Location
Area in square feet
Number of bedrooms
Number of bathrooms
The final trained model can be used to build a simple frontend or API for real-time predictions.

✅ Results
Achieved a good R² score on test data using Linear Regression.
Removed outliers and multicollinearity, resulting in more reliable predictions.
Trained model is saved using Pickle for deployment.

🚀 Future Work
Build a Flask or Django web app interface
Deploy as a REST API using Flask
Enhance model using advanced regression techniques (XGBoost, RandomForest)
Integrate live data for price trends

👩‍💻 Author
Tanuja Mahendrakar
Bengaluru House Price Prediction ML Project










# food-price-and-nurition-prediciton
Food Price & Nutrition Prediction
Project Overview

The Food Price & Nutrition Prediction System is a Machine Learning project designed to predict the price and nutritional values of food items based on various input features such as food category, ingredients, calories, protein, fat, carbohydrates, and other nutritional information.

This project helps users analyze food data efficiently and provides predictions that can support:

Healthy food selection
Diet planning
Food market analysis
Smart restaurant systems
Nutrition-aware applications
Features
 Predict food prices using Machine Learning
 Analyze nutritional values of food items
 Data preprocessing and feature engineering
 Multiple ML models for better accuracy
 User-friendly interface for predictions
 Visualization of food trends and nutrition data
 Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Flask / Streamlit (if used)
Jupyter Notebook
 Dataset

The dataset contains information about:

Food Name
Category
Calories
Protein
Fat
Carbohydrates
Sugar
Fiber
Vitamins
Price

The dataset is cleaned and preprocessed before training the model.

 Machine Learning Workflow
Data Collection
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training
Model Evaluation
Prediction System Deployment
 Models Used
Linear Regression
Random Forest Regressor
Decision Tree Regressor
XGBoost Regressor
 Evaluation Metrics

The model performance is evaluated using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
 Installation
# Clone the repository
git clone https://github.com/your-username/food-price-nutrition-prediction.git

# Navigate to project folder
cd food-price-nutrition-prediction

# Install dependencies
pip install -r requirements.txt
 Run the Project
python app.py

or

streamlit run app.py
 Project Output
Predicts estimated food price
Displays nutritional analysis
Generates visual insights and charts
Project Structure
Food-Price-Nutrition-Prediction/
│
├── dataset/
├── notebooks/
├── models/
├── static/
├── templates/
├── app.py
├── requirements.txt
├── README.md
└── model.pkl
 Future Enhancements
Deep Learning integration
Real-time food market analysis
Mobile application support
Personalized diet recommendations
API integration for live food pricing
 Author

KABEESH J

Passionate about Machine Learning and AI
Interested in Data Science and Deep Learning Projects
Conclusion

This project demonstrates how Machine Learning can be applied to food analytics for predicting prices and nutritional values. It combines data analysis, predictive modeling, and visualization to build an intelligent and practical solution.

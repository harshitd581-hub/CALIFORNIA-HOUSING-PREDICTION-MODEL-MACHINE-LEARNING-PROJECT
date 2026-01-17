🏠 California Housing Price Prediction Model (Machine Learning)

This project implements a Machine Learning regression pipeline to predict median house prices in California using socioeconomic and geographical features.  
The model is trained on the California Housing Dataset and supports batch predictions using CSV files, with model persistence handled via Joblib.

 📌 Project Motivation

Accurate housing price prediction is crucial for:
- Real estate analytics
- Urban planning
- Investment decision-making
- Policy analysis

This project demonstrates an end-to-end ML workflow, from data preprocessing to model deployment readiness, making it suitable for internship applications and academic projects.

 🧠 Problem Statement

Given district-level data such as income, house age, number of rooms, and population,  
predict the median house value** for that region.

This is a supervised regression problem.


 📂 Dataset Description

The dataset (`housing.csv`) contains the following features:

| Feature | Description |

longitude` | Longitude of the district |
latitude` | Latitude of the district |
housing_median_age` | Median age of houses |
total_rooms` | Total rooms in the district |
total_bedrooms` | Total bedrooms |
population` | Population of the district |
households` | Number of households |
median_income` | Median income (scaled) |
median_house_value` | **Target variable** |



 Tech Stack Used

Programming Language:** Python  
Libraries:**
  - NumPy
  - Pandas
  - Scikit-learn
  - Joblib
  ML Model:** Regression model (Linear / Tree-based depending on script version)


 Machine Learning Workflow

1. Data Loading & Inspection
2. Data Cleaning & Preprocessing
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Model Serialization using Joblib
7. Batch Prediction using CSV input
8. Output saved as CSV

📁 Project Structure
CALIFORNIA-HOUSING-PREDICTION-MODEL-MACHINE-LEARNING-PROJECT

 housing.csv # Original dataset
 input.csv # Sample input data
 input - Copy.csv # Backup input
 output.csv # Model predictions

main_old.py # Initial model training script
 main BY JOBLIB.py # Optimized script with model persistence

 README.md # Project documentation





▶️ How to Run the Project

Step 1: Clone the Repository
```bash
git clone https://github.com/harshitd581-hub/CALIFORNIA-HOUSING-PREDICTION-MODEL-MACHINE-LEARNING-PROJECT.git
cd CALIFORNIA-HOUSING-PREDICTION-MODEL-MACHINE-LEARNING-PROJECT

Step 2: Install Dependencies
pip install numpy pandas scikit-learn joblib

Step 3: Run the Model
python "main BY JOBLIB.py"



📊 Output

The model generates house price predictions

Predictions are saved in output.csv

Output format is CSV, suitable for further analysis or integration

💡 Key Highlights

End-to-end ML workflow

Regression-based prediction system

Model persistence using Joblib

CSV-based batch prediction support

Clean and reusable project structure

🚀 Future Enhancements

Add model evaluation metrics (RMSE, R²)

Hyperparameter tuning

Compare multiple regression models

Deploy using Flask / FastAPI

Build a web-based UI for predictions

📌 Suitability

 Internship Projects
 Academic Submissions
 Machine Learning Portfolio
 GitHub Showcase

👤 Author

Harshit Dubey
Machine Learning & Data Science Enthusiast


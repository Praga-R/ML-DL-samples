# ML-DL-samples

# Bike Rental Prediction

This repository contains code and data for predicting bike rental counts using different machine learning models.  
It is designed as a learning project to compare traditional regression methods with ensemble techniques.

---

## 📂 Repository Contents

| File/Folder            | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `linear_regression.py` | Implements a Linear Regression model to predict bike rental counts.         |
| `random_forest.py`     | Implements a Random Forest model for more robust predictions.               |
| `bike.csv`             | Dataset containing historical bike rental information (features + target).  |
| `README.md`            | Documentation about the project, usage, and instructions.                   |

---

## 🚴 Dataset
- **File:** `bike.csv`  
- **Contents:** Includes features such as date, weather conditions, temperature, humidity, and rental counts.  
- **Target Variable:** Number of bikes rented.  

---

## ⚙️ Models
1. **Linear Regression (`linear_regression.py`)**
   - Simple baseline model.
   - Assumes linear relationship between features and rental counts.

2. **Random Forest (`random_forest.py`)**
   - Ensemble model using decision trees.
   - Captures non-linear relationships and interactions between features.

---

## ▶️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/username/bike-rental-prediction.git
   cd bike-rental-prediction

📊 **Expected Output:**

1) Model training results (R² score, Mean Squared Error).

2) Comparison of predictions between Linear Regression and Random Forest.

3) Insights into which model performs better on the dataset.

📝 **Notes:**

This project is for educational purposes to practice machine learning concepts.

Dataset is small and may not generalize to real-world bike rental systems.

**Future improvements could include:**

1) Feature engineering (e.g., adding holidays, time of day).

2) Hyperparameter tuning for Random Forest.

3) Trying other models (Gradient Boosting, Neural Networks).

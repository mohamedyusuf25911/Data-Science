# Jigarthanda Sales Prediction

Predict daily Jigarthanda sales using weather, temperature, day type, and customer data. 
This project demonstrates data preprocessing, machine learning modeling, and evaluation using regression techniques.

---

## Dataset

The dataset contains the following columns:

- `Temperature`: Encoded as categorical
- `Weather`: Encoded as categorical
- `DayType`: Encoded as categorical (weekday, weekend, holiday)
- `Customers`: Number of customers per day
- `Jigarthanda_Sales`: Target variable (number of Jigarthanda sold)

---

## Features

- Temperature  
- Weather  
- DayType  
- Customers  

---

## Models Used

- Random Forest Regressor  
- Decision Tree Regressor  

**Evaluation metrics:**

- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

---

## Model Performance

| Model           | R² Score | MAE   | RMSE  |
|-----------------|----------|-------|-------|
| Random Forest   | 0.917    | 4.36  | 5.11  |
| Decision Tree   | 0.902    | 4.64  | 5.56  |

---

## Key Findings

- Random Forest performed slightly better than Decision Tree.  
- Most important feature: `Customers`.  
- Other factors like `Temperature`, `Weather`, and `DayType` also influence sales.

---

## Data Preprocessing Steps

1. Encode categorical features using `LabelEncoder`  
2. Split data into train (80%) and test (20%) sets  
3. Optional: Hyperparameter tuning using `GridSearchCV`  

---

## Visualization

- Scatter plots: Actual vs Predicted sales  
- Residual distribution  
- Feature importance (Random Forest)  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/jigarthanda-sales-prediction.git


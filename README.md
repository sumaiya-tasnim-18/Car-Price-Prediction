# 🚗CAR_PRICE_PREDICTION – Using Machine Learning
This repository demonstrates a machine learning workflow for predicting used car selling prices. It leverages data preprocessing, feature engineering, categorical encoding, and Random Forest regression to estimate prices accurately while providing insights into key factors affecting car value.

# 📇 Project Overview
    • Dataset: car data.csv containing car details like year, present price, kilometers driven, fuel type, transmission, ownership, and selling price
    • Tools: Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
    • Focus Areas: Data cleaning, feature engineering (Car Age, target encoding), Random Forest regression, log-transformed price prediction, model evaluation, and visual insights

# ╰┈➤ 📝 Steps Breakdown
    • Step 1: Loaded and inspected the dataset, removed duplicates, and checked for missing values and data types.
    • Step 2: Created new features such as Car Age, and encoded categorical features like Fuel_Type, Selling_type, and Transmission.
    • Step 3: Applied log transformation on Selling_Price to stabilize variance and improve model performance.
    • Step 4: Split the dataset into training and testing sets and trained a Random Forest Regressor with hyperparameter tuning.
    • Step 5: Evaluated model performance using metrics including RMSE, R² Score, and residual analysis.
    • Step 6: Developed a prediction function accepting human-readable inputs to estimate car selling prices in lakhs.
    • Step 7: Created comprehensive visual insights: price distribution, selling price vs present price, selling price vs car age, fuel & transmission effects, feature importance, and model performance charts (Actual vs Predicted, Residuals).

# 🎯 Outcome
Developed a robust Random Forest model achieving an enhanced R² score of 0.58 and RMSE of 3.28 for predicting car prices. The project demonstrates the impact of key features like Present_Price, Year, and Car_Age, with visual analytics providing interpretability and actionable insights for potential buyers or sellers.

# 📌Project Insights:
Predicted Selling Price: ₹6.18 lakh
<img width="1982" height="1524" alt="image" src="https://github.com/user-attachments/assets/1d144854-d3a1-431e-b69b-9c347c02750a" />

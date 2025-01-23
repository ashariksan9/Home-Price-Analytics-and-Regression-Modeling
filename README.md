# Home Price Analytics and Regression Modeling

## Overview
This project involves building a machine learning model using Linear Regression to predict house prices based on various features such as location, property type, and size. The dataset contains detailed information about houses listed for sale, providing an opportunity to analyze and predict prices accurately.

---

## Purpose
The project is a graded assignment aimed at:
- Understanding regression concepts with Linear Regression.
- Preparing data for use in a Linear Regression model.
- Implementing Linear Regression to make predictions.

---

## Problem Statement
As a data scientist at PT. Rumah Baru Keluarga, your task is to develop a machine learning model that can accurately predict house prices. This will help customers make informed decisions by estimating property costs based on their preferences and criteria.

---

## Background
PT. Rumah Baru Keluarga offers real estate services, including price inquiries, document processing, and accurate cost estimation. By leveraging machine learning, the company aims to enhance its services and provide even more precise recommendations to its clients.

---

## Output
The primary output of this project is a trained Linear Regression model capable of predicting house prices based on user-defined criteria. Additionally, insights from the data analysis will be provided to inform decision-making.

---

## Dataset Description
The dataset used is `house-price-v2.csv`, which contains the following columns:

- **area:** Specific area of a house
- **city:** City where the house is located
- **latitude & longitude:** Geographic coordinates
- **property_type:** Type of property
- **bedrooms & bathrooms:** Number of bedrooms and bathrooms
- **land_area & building_area:** Land and building size in square meters
- **floors:** Number of floors
- **maid_bedrooms & maid_bathrooms:** Maid-specific rooms
- **certificate:** Type of ownership certificate
- **voltage:** Electricity capacity
- **building_age:** Age of the building
- **year:** Year built
- **condition:** Current condition of the house
- **garage & carport:** Availability of garage and carport
- **price:** Price of the house

---

## Methodology
The project includes:
1. **Exploratory Data Analysis (EDA):** Understanding the dataset and identifying patterns or insights.
2. **Feature Engineering:** Preparing data for model training, including handling missing values, encoding, and normalization.
3. **Model Building:** Implementing Linear Regression and evaluating its performance.
4. **Model Evaluation:** Assessing model accuracy and identifying areas for improvement.
5. **Model Inference:** Using the model to predict house prices for unseen data.

---

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

---

## File Structure
1. **`notebook/`**: Contains Jupyter notebooks for data analysis, model building, and evaluation.
   - `EDA.ipynb`: Exploratory Data Analysis and visualization.
   - `Model_Building.ipynb`: Model training and evaluation.
   - `Model_Inference.ipynb`: Prediction using the trained model.
2. **`data/`**: Includes the dataset (`house-price-v2.csv`).
3. **`models/`**: Saved models and relevant files.
4. **`README.md`**: Project documentation.

---

## Strengths
1. **Insightful EDA:**
   - Identified patterns, such as the top areas for luxury houses and the impact of house age on price.
   - Categorized voltage levels for a better understanding of property segmentation.
2. **Clear Recommendations:**
   - Provided actionable insights, such as recommending newer houses based on price and condition.
3. **Scalable Approach:**
   - The framework is modular, allowing for the addition of advanced models and new data features.

---

## Weaknesses
1. **Model Limitations:**
   - Linear Regression struggled with non-normal data distribution and the presence of outliers.
   - Low R² score, indicating suboptimal fit.
2. **Feature Correlation Issues:**
   - Some features, such as latitude and longitude, showed minimal correlation with house prices.
   - Negative correlation observed for certain features like year, suggesting data quality or relevance issues.
3. **Overfitting:**
   - Observed in Lasso Regression due to potential noise in the dataset.

---

## Future Improvements
1. Perform more rigorous feature selection to eliminate irrelevant or noisy data.
2. Explore additional models like Ridge Regression or Elastic Net to handle multicollinearity and overfitting better.
3. Apply advanced data preprocessing techniques to address outliers and ensure normal data distribution.

---

## References
- Dataset: Provided as part of the assignment.
- Linear Regression techniques: Scikit-learn documentation.

---

## Contact
Feel free to reach out if you have any questions or suggestions regarding this project:

- **Email**: ashar4iksan@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/muhammadasharihsan

Thank you for reviewing this project! If you found it helpful or have feedback, I'd love to hear from you.

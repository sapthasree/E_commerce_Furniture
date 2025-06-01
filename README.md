# Predicting Furniture Sales Using E-commerce Data (2024)
## 🧰 Tools & Technologies
Programming: Python  

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

Others: Jupyter Notebook, Excel (for quick views)  

## 🎯 Objective
Build a predictive model to estimate furniture sales on an e-commerce platform using product attributes like price, title, and promotional tags.  

## 📥 1. Data Collection
The dataset is available in CSV format and contains 2,000 furniture product entries. Each entry includes:  

productTitle  

originalPrice  

price  

sold  

tagText (e.g., Free shipping, Shipping cost, etc.)  

## 🧹 2. Data Preprocessing
Removed null values  

Cleaned price strings  

Encoded categorical columns  

Checked for and removed duplicates  

Converted price fields to numeric format  

## 📊 3. Exploratory Data Analysis (EDA)
Visualized relationships between features and the target variable (sold)  

Analyzed distribution of sales  

Assessed the distribution of tagText  

Performed correlation analysis between numeric features  

## 🧠 4. Feature Engineering
Created a new feature for discount percentage from originalPrice and price  

Converted productTitle to numerical features using TF-IDF  

Encoded tagText using Label Encoding  

## 🏗️ 5. Model Training
Two models were trained to predict the number of items sold:  

Linear Regression  

Random Forest Regressor  

Data was split into training and testing sets, cleaned, and imputed before training.  

## 📈 6. Model Evaluation
Models were evaluated using:  

Mean Squared Error (MSE)  

R-squared Score (R²)  

## ✅ 7. Conclusion
Random Forest Regressor outperformed Linear Regression in predicting sales.  

The model performance could be improved with cleaner pricing data (some originalPrice values were missing or unreliable).  

Insights from the analysis can help e-commerce platforms optimize product listings and pricing strategies.  

This project serves as a potential foundation for building an AI-powered pricing strategy tool for online marketplaces.  

## 📊 Output Summary
Linear Regression Model  

MSE: 176,394.70  

R²: -0.5066  

Random Forest Model  

MSE: 136,072.93  

R²: -0.5066  

# 💻 Laptop Price Prediction

This project focuses on building a machine learning model that can accurately predict the price of a laptop based on various specifications like brand, processor, RAM, storage, GPU, and more.

# Dataset

Source: `laptopPrice.csv`
The dataset contains the following columns:
- `Brand`
- `Processor`
- `RAM`
- `Storage (SSD & HDD)`
- `Graphics Card`
- `Price`

# Project Goals

1. Data Exploration
   - Checked for nulls, feature types, and unique values.
     
2. Feature Engineering 
   - Converted string specs to numerical values (e.g., "8 GB" → 8).
   - Encoded categorical columns using LabelEncoder.
     
4. Model Selection & Training
   - Trained **Random Forest Regressor** and **Gradient Boosting Regressor**.
     
5. Evaluation
   - Evaluated using MAE and RMSE.
   - Applied cross-validation to validate results.
     
# Libraries Used

- `pandas`, `numpy` - data handling
- `matplotlib`, `seaborn` - data visualization
- `scikit-learn` - machine learning models and metrics

# Results

------------------------------------------------------------------
| Model              | MAE                 | RMSE                |
|--------------------|---------------------|---------------------|
| Random Forest      | 12199.762132683984  | 24813.383437472996  |
| Gradient Boosting  | 13356.02371938398   | 25726.55367473458   |
------------------------------------------------------------------

# How to Run

1. Open the project in Google Colab or Jupyter Notebook
2. Upload the dataset: `laptopPrice.csv`
3. Run the notebook cells step-by-step:
   - Data Cleaning
   - Exploratory Data Analysis (EDA)
   - Feature Engineering
   - Model Training & Evaluation
   - Cross-Validation

# Conclusion
 
- Random Forest and Gradient Boosting performed better than Linear Regression  
- Cross-validation gave more reliable performance estimation

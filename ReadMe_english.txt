This project presents a complete and robust data science pipeline designed to predict the Comfort Index based on weather data. It covers all essential steps including data preprocessing, exploratory analysis, advanced modeling, and detailed evaluation.

Key features of this project include:

Data Preparation: Careful cleaning of missing values and feature scaling to prepare the data for efficient and stable model training.

Exploratory Data Analysis (EDA): Visualization of feature distributions such as wind direction and pressure, before and after filling missing values, providing insights into data quality improvements.

Diverse Regression Models: Implementation of multiple powerful regression algorithms:

Linear Regression as a baseline

Tree-based ensembles such as XGBoost, LightGBM, Random Forest, and Gradient Boosting

Support Vector Regression (SVR)

Deep learning using LSTM networks to capture temporal dependencies in sequential data

Advanced Stacking Ensemble:
A core highlight is the stacked ensemble model that combines predictions from all base regressors using Ridge Regression as a meta-learner. This approach significantly enhances the predictive performance compared to any single model alone.

Missing Data Imputation with XGBoost:
Missing values in critical features (e.g., wind direction and pressure) are intelligently filled using an XGBoost-based imputation method. This step markedly improves model accuracy, as evidenced by higher R² scores after imputation.

Comprehensive Model Evaluation:
Models are assessed using MAE, RMSE, and R² metrics, accompanied by intuitive visualizations including feature importance and performance comparisons.

Export of Results:
Intermediate data, plots, and evaluation summaries are saved into Excel files for transparency and future reference.

Together, these components demonstrate an effective integration of classical machine learning, deep learning, and ensemble techniques, providing a reliable framework for meteorological regression tasks.


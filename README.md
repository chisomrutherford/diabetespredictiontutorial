# Diabetes Prediction using Machine Learning

This project aims to predict diabetes using various machine learning models. The dataset used is the Pima Indians Diabetes Database, which contains medical and demographic information of female patients of Pima Indian heritage.

## Project Workflow

1. **Data Loading and Exploration:**
   - Load the diabetes dataset using pandas.
   - Explore the data using descriptive statistics, histograms, and density graphs.
   - Identify missing values and outliers.

2. **Data Preprocessing:**
   - Handle missing values by imputing with median values based on the 'Outcome' variable.
   - Detect and handle outliers using the Local Outlier Factor (LOF) method.

3. **Feature Engineering:**
   - Create new features based on existing ones to improve model performance.
   - Examples: BMI categories, Insulin score categories, and Glucose categories.

4. **Data Transformation:**
   - Convert categorical features into numerical using one-hot encoding.
   - Scale numerical features using RobustScaler.

5. **Model Building and Evaluation:**
   - Split the data into training and testing sets.
   - Train various machine learning models: Logistic Regression, K-Nearest Neighbors, Support Vector Machine, and Decision Tree.
   - Evaluate model performance using accuracy score, confusion matrix, and classification report.

6. **Hyperparameter Tuning:**
   - Use GridSearchCV to find the optimal hyperparameters for the Support Vector Machine model.

## Results

The project compares the performance of different machine learning models in predicting diabetes. The results are presented in terms of accuracy, precision, recall, and F1-score.

## Dependencies

- Python 
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Statsmodels
- Missingno

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook to execute the code.

## Conclusion

This project demonstrates the application of machine learning techniques to predict diabetes. The results provide insights into the effectiveness of different models and the importance of data preprocessing and feature engineering.


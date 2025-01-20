# House Price Prediction Using Machine Learning

## Description
This project leverages advanced machine learning techniques to predict house prices based on a dataset with 79 explanatory variables. The goal is to build an accurate predictive model through key data science steps: cleaning, exploration, feature engineering, and modeling.

## Key Features
- **Data Cleaning and Exploration**: Analysis of 79 variables, handling missing values, and addressing non-normal distributions.
- **Feature Engineering**: Transforming numerical and categorical variables, creating new features, and normalization.
- **Advanced Modeling**:
  - Benchmarking several models, including Lasso, XGBoost, and StackedRegressor.
  - Hyperparameter optimization to enhance predictive performance.
- **Performance Evaluation**: Calculating RMSE (Root Mean Squared Error) on a hidden test dataset.

## Results
- **RMSE**: 0.12 on a hidden test dataset, demonstrating excellent predictive accuracy.

## Dependencies
- Python (version >= 3.7)
- Key Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - xgboost
- Additional tools: Google Colab (for execution and file management via Google Drive).

## File Structure
- **Main Notebook**: `House_prices_regression.ipynb`
- **Data**:
  - `train.csv`: Training dataset
  - `test.csv`: Test dataset
- **Outputs**:
  - Data exploration plots
  - Saved models and performance evaluations

## Instructions
1. Clone this repository or download the files.
2. Install dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook in a Jupyter environment or Google Colab.
4. Ensure the `train.csv` and `test.csv` files are available in the working directory.

## Main Steps
1. **Mount Files**: The notebook includes instructions to mount Google Drive and access the required files.
2. **Data Preparation**: Clean and normalize the data as guided in the notebook.
3. **Feature Engineering**: Transform variables and apply scaling and encoding techniques.
4. **Modeling**: Train predefined models and compare their performances.
5. **Evaluation**: Assess performance on the hidden test dataset.

## Author
Maxime LAFONT, 10/2024


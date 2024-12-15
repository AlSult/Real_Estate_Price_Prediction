# Real Estate Price Prediction using ML models.

This project aims to predict rental prices of apartments based on their features, such as location, size, and amenities. 
It uses machine learning models and Python.

## Project Structure
- `data/`: Contains the dataset for training and testing.
- `notebooks/`: Jupyter notebooks for exploratory data analysis (EDA) and model development.
- `scripts/`: Python scripts for data processing and training the model.

## Tools and Libraries
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- 
## Steps Taken
1. **Data Cleaning**: Removed rows with missing values and filled others.
2. **Data Preprocessing**: Encoded categorical variables and scaled the features.
3. **Model Training**: Trained models like Linear Regression, Random Forest, etc.
4. **Model Evaluation**: Evaluated using MAE, MSE, and R².

## Results
- Linear Regression: R² = 1.0, MAE = 2.87e-16
- Random Forest: R² = 0.9999, MAE = 0.001
- Ridge Regression: Best results with R² = 1.0 and MAE = 0.0001.

## Next Steps
- Implement cross-validation.
- Tune hyperparameters for better performance.

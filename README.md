# Predict Medical Insurance Charges - Machine Learning Regression

A machine learning regression project built from scratch to predict medical insurance charges based on various factors. This project demonstrates end-to-end implementation of multi-linear regression with cross-validation using Jupyter Notebooks.

## Overview

This project uses **Multi-Linear Regression (MLR)** and **K-Folds Cross-Validation** to build a predictive model that estimates medical insurance costs based on input features such as age, BMI, smoking status, and more.

## Features

- **Data Analysis & Visualization**: Comprehensive exploratory data analysis with matplotlib and seaborn
- **Multi-Linear Regression**: Built from scratch to predict insurance charges
- **K-Folds Cross-Validation**: Robust model evaluation and validation
- **Feature Engineering**: Processing and preparation of input features
- **Model Performance**: Detailed metrics and performance evaluation

## Technologies Used

- Python 3
- Jupyter Notebook
- Pandas (data manipulation)
- NumPy (numerical computations)
- Matplotlib & Seaborn (data visualization)
- Scikit-learn (machine learning)

## Installation & Setup

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Steps to Run

1. **Install Python3 and Jupyter Notebook**
   ```bash
   pip install jupyter notebook
   ```

2. **Install Required Libraries**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Setup Project Files**
   - Ensure `model.ipynb` and `insurance.csv` are in the same directory

4. **Configure Data Path**
   - Open `model.ipynb` in a text editor
   - Update the CSV path in `pd.read_csv('your_path')` to match your file location

5. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

6. **Run the Model**
   - Click on `model.ipynb` to open the notebook
   - Execute each cell sequentially to see the analysis and results

## Project Structure

```
predict-medical-insurance-charges-MLR/
├── model.ipynb          # Main ML model and analysis
├── insurance.csv        # Dataset
└── README.md            # Documentation
```

## Dataset

The project uses medical insurance data containing features like:
- Age
- Sex
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region

Target variable: Medical insurance charges

## Model Output

The model provides:
- Regression coefficients for each feature
- Model performance metrics (R², MAE, MSE)
- Cross-validation scores
- Visualizations of predictions vs actual values

## License

This project is open source and available for educational purposes.

## Author

Built from scratch by Rishi-1482
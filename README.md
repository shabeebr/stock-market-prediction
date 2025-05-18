# stock-market-prediction
![image](https://github.com/user-attachments/assets/de928dc9-605f-4a18-925d-52ec6fd60541)

# Stock Market Prediction Project

This project implements a simple stock market prediction model using **Linear Regression**. It leverages historical stock data to predict future prices.

---

## Project Files

- **linear_regression_stock_model.pkl**  
  The saved trained Linear Regression model serialized with `pickle`. You can load this model to make predictions without retraining.

- **stockmarket_prediction.ipynb**  
  Jupyter Notebook demonstrating the entire workflow: data loading, preprocessing, model training, evaluation, and visualization.

- **stockmarket_prediction.py**  
  Python script version of the stock market prediction pipeline. Useful for running the model training and predictions outside of the notebook environment.

---

## How to Use

1. **Download and Prepare Data**  
   Download the dataset from Kaggle (`engrhaseebjan/a-simple-stock-market-prediction-dataset`) and place it in the appropriate directory.  
   Alternatively, use the KaggleHub tool as shown in the notebook/script to download it programmatically.

2. **Train the Model (Optional)**  
   Run the notebook or the script to train the Linear Regression model on the historical stock data.

3. **Make Predictions**  
   Load the saved model `linear_regression_stock_model.pkl` to predict stock prices on new data.

---

## Dependencies

- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- scikit-learn  
- kagglehub (for dataset download)

Install the dependencies with:

```bash
pip install pandas numpy matplotlib scikit-learn kagglehub


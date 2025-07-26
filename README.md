
# Gold Price Prediction using Machine Learning

This project implements a simple machine learning model to predict the future prices of gold using historical data. The model leverages Python libraries such as pandas, scikit-learn, and matplotlib to preprocess data, train a regression model, and visualize results.

---

## 📌 Project Description

Gold prices are influenced by various economic indicators. Predicting its future value can be beneficial for investment decisions and economic analysis. In this project:

- We use historical data from a CSV file containing gold price trends and related features.
- We apply data preprocessing and feature selection.
- We use a **Linear Regression** model to predict gold prices.
- We visualize the predicted vs actual values.

---

## 🛠️ Technologies & Libraries Used

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn

---

## 📂 Dataset

The dataset used contains information such as:

- Date  
- SPX (S&P 500 Index)  
- GLD (Gold ETF price)  
- USO (Oil price)  
- SLV (Silver ETF price)  
- EUR/USD exchange rate

📁 Dataset Link: [Download from GeeksforGeeks](https://media.geeksforgeeks.org/wp-content/uploads/20230516172204/gld_price_data.csv)

---

## 🚀 How to Run the Project

1. **Clone the repository or download the project files.**

```bash
git clone https://github.com/yourusername/gold-price-prediction.git
cd gold-price-prediction
```

2. **Install the required libraries**

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. **Place the dataset (`gld_price_data.csv`) in the project directory.**

4. **Run the script**

```bash
python gold_price_prediction.py
```

---

## 📈 Output

- The model prints the accuracy score.
- A plot showing actual vs predicted gold prices is generated using `matplotlib`.

---

## 🧠 Machine Learning Model

- **Algorithm Used**: Linear Regression
- **Feature**: Independent variables include SPX, USO, SLV, EUR/USD.
- **Target**: GLD (Gold Price)
- **Train/Test Split**: 80/20

---

## 📊 Sample Visualization

The program plots the predicted vs actual gold prices using test data:

```
Predicted vs Actual Gold Prices
```

---

## ✅ Future Improvements

- Try other regression models like Random Forest, XGBoost, etc.
- Incorporate more features such as inflation rates, interest rates, etc.
- Perform hyperparameter tuning for better results.
- Deploy using Flask or Streamlit for web-based access.

---

## 🙌 Acknowledgements

- Project inspired by [GeeksforGeeks Tutorial](https://www.geeksforgeeks.org/gold-price-prediction-using-machine-learning/)

---

## 📃 License

This project is for educational purposes. Refer to the original tutorial or dataset for licensing details.

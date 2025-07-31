# 📈 TCS Stock Price Prediction using LSTM

This project aims to predict the closing stock prices of **Tata Consultancy Services (TCS)** using a Long Short-Term Memory (LSTM) neural network. It uses historical stock data and builds a time series forecasting model using deep learning techniques.

---

## 🔍 Project Overview

- 📊 Input: Historical stock data of TCS (CSV file)
- 🧠 Model: LSTM Neural Network (TensorFlow/Keras)
- 📈 Output: Predicted closing prices
- 📉 Visualization: Actual vs Predicted prices plotted

---

## 📂 Files

- `Stock_Price_Prediction.ipynb` – Main notebook with all the code
- `tcs_stock.csv` – Dataset (cleaned and used for training)
- `requirements.txt` – Python dependencies
- `README.md` – Project description (this file)

---

## ⚙️ How to Run

1. **Clone or copy the project folder** to your system.

2. **Create a virtual environment (optional but recommended)**:
   ```bash
   conda create -n stockenv python=3.10
   conda activate stockenv
   
3. **Install required packages:
pip install -r requirements.txt

4. **Launch Jupyter Notebook:
jupyter notebook

5. **Open Stock_Price_Prediction.ipynb and run all cells:
   Click on Kernel > Restart & Run All
   
---
📷 Output
The model will plot the actual vs predicted TCS stock prices, showing how closely the LSTM model has learned the pattern.

---
🛠 Technologies Used

Python

TensorFlow / Keras

Pandas

NumPy

Matplotlib

Scikit-learn

---
✅ Results
The model shows low prediction loss (~0.002x) after training.

Accurate trend prediction of closing stock prices.




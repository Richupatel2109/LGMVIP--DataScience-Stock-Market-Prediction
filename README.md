# 📈 Stock Market Prediction Using Stacked LSTM

This project demonstrates how to predict stock prices using a **Stacked LSTM (Long Short-Term Memory)** model. The dataset used consists of historical stock prices of NSE-TATAGLOBAL, and the model is built using TensorFlow/Keras.

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/stock-lstm-predictor.git
cd stock-lstm-predictor
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Open the Notebook
##### Open notebooks/Stock_Prediction_LSTM.ipynb in Jupyter or Colab to run the full model training and prediction workflow.
---
## 🧠 Model Overview

  Model Architecture: 3 stacked LSTM layers + Dense
  
  Loss Function: Mean Squared Error

  Optimizer: Adam
  
  Sequence Length: 100
  
  Prediction Target: Closing stock price
---
## 📊 Output Visualization

Red: Original training data

Blue: Predicted training data

Green: Predicted test data

---
## 📦 Dependencies

All dependencies are listed in requirements.txt. Key libraries include:

    numpy
    pandas
    matplotlib
    seaborn
    sklearn
    tensorflow
---
## 📁 Dataset

The dataset is a CSV file named NSE-TATAGLOBAL.csv, containing:

    Open, High, Low, Last, Close

    Total Trade Quantity

    Turnover (in Lacs)

    Date
---
### 📦 requirements.txt

```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow
```
---

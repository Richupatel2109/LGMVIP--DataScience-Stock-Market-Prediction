# 📈 Time Series Forecasting using Stacked LSTM

This project demonstrates how to use a **Stacked LSTM (Long Short-Term Memory)** model for time series prediction. The notebook walks through data preprocessing, model construction, training, and evaluation using TensorFlow/Keras.

---

## 🧠 What is a Stacked LSTM?

Stacked LSTMs are deep LSTM networks that allow multiple LSTM layers to learn hierarchical temporal representations of sequential data. This approach improves model learning for complex patterns in time series.

---

## 📁 Project Structure

```
stacked-lstm-sequence-prediction/
├── using_stackedLSTM.ipynb       # Main notebook
├── data/                         # Input data (if needed)
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/stacked-lstm-sequence-prediction.git
cd stacked-lstm-sequence-prediction
```

### 2. Set up a virtual environment (optional but recommended)

```bash
python3 -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
```

### 3. Install Python dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook and run all cells

Navigate to `using_stackedLSTM.ipynb` in the Jupyter interface and execute each cell step-by-step to view results.

---

## 📊 Features Demonstrated

- Time series data preprocessing
- Normalization using `MinMaxScaler`
- Splitting data into train/test sequences
- Building stacked LSTM architecture using `Sequential` API
- Model evaluation using MSE/MAE
- Visualization of predictions vs actual values

---

## 🛠 Tools & Libraries

- Python 3.9+
- TensorFlow & Keras
- NumPy, Pandas
- Matplotlib
- Scikit-learn

---
## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

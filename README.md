
# Electricity Consumption Forecasting Using LSTM

This project demonstrates how to use a Long Short-Term Memory (LSTM) neural network to predict future electricity consumption based on historical time series data. The aim is to build a model that accurately captures trends and patterns to make reliable forecasts.

## Problem Statement
Traditional methods struggle to capture the temporal dependencies in electricity demand data. This project applies deep learning (LSTM) to predict electricity consumption using time series forecasting.

## Objective
To train an LSTM model that can predict future electricity usage by minimizing the error between actual and predicted values — making the predicted graph closely follow the actual values.

## Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

## 📊 Dataset
You can use any public dataset related to electricity consumption. For this project, the dataset includes:
- Date or time column
- Electricity usage values (target)

## Preprocessing Steps
- Time series formatted with timestamps
- Scaled data using MinMaxScaler
- Reshaped input for LSTM

## Model Architecture
- LSTM layer(s)
- Dense output layer
- Loss function: Mean Squared Error (MSE)
- Optimizer: Adam

## Training Configuration
- Epochs: 50
- Batch size: 32
- Validation split: Yes (using train_test_split)
- Metrics: Training vs Validation Loss

## 📈 Results
- The model achieves a close match between predicted and actual values.
- Loss curves show convergence.
- Graphs indicate the model successfully follows the pattern of real electricity usage.


## How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook or script

## 📁 Files Included
- `electricity_lstm.ipynb`: Jupyter notebook with all steps
- `README.md`: This file
- `model.png`: Sample output graph (optional)
- `data.csv`: Dataset file (not included due to size/privacy)
- https://github.com/Preetttttt/smart-grid.git

## 📌 Conclusion
LSTM-based time series models can effectively predict electricity consumption. This project demonstrates a working implementation with scope for improvement using more layers, better tuning, and longer sequences.

## Project link:
https://github.com/Preetttttt/smart-grid.git

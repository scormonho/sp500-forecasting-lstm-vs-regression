# LSTM vs Regression: Time Series Forecasting

This project compares the performance of a traditional regression model with a Long Short-Term Memory (LSTM) neural network for time series forecasting. It demonstrates how deep learning can be applied to sequential data and evaluates its effectiveness compared to simpler statistical approaches.

## 📁 Project Structure

- `LSTM v Regression.ipynb`: Main notebook comparing regression and LSTM for time series prediction.

## 📊 Objective

The primary goal is to:
- Forecast future values in a time series dataset.
- Compare the accuracy of regression and LSTM-based models.
- Visualize the results and understand the impact of different modeling approaches on forecasting performance.

## ⚙️ Used libraries:
- `numpy`
- `pandas`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `tensorflow` (for the LSTM model)

## 🧹 Data Preprocessing

- Data is read using `pandas`.
- For LSTM, the data is reshaped into 3D format: `(samples, time steps, features)`.
- For Regression, the data is reshaped into 2D format: `(samples, features)`.

## 🧠 Models

- **Regression**: Standard linear regression applied to preprocessed features.
- **LSTM**: A sequential deep learning model built using TensorFlow/Keras with one or more LSTM layers.

## 📈 Evaluation

- Evaluation metrics such as Root Mean Squared Error (RMSE) or Mean Absolute Error (MAE) are used.
- Visualizations compare true vs predicted values for both models.

## 📝 Notes

- The project highlights the advantages of deep learning in capturing temporal dependencies.
- Useful as a baseline for more advanced forecasting tasks.
- Future Improvements: form trading strategies from LSTM errors 

# Type-1-Diabetes-Prediction-ARIMA

Predicting blood glucose levels in Type 1 diabetes (T1D) is of utmost importance due to its direct impact on patient safety, long-term health, and overall quality of life. Maintaining blood sugar within a safe range is critical for preventing life-threatening complications and improving daily diabetes management. One of the most immediate concerns in T1D is preventing hypoglycemia (low blood sugar) and hyperglycemia (high blood sugar). Predicting glucose levels enables timely interventions, such as consuming carbohydrates to prevent a sugar crash or adjusting insulin doses to avoid dangerous spikes.

Accurate blood glucose prediction in Type 1 diabetes is essential for preventing long-term complications such as nerve damage, kidney failure, heart disease, and blindness by maintaining better glycemic control.

Since glucose levels are influenced by multiple factors like diet, stress, and exercise, predictive models help reduce the mental and physical burden on patients and caregivers by providing automated assistance.

## 📍ARIMA

ARIMA (AutoRegressive Integrated Moving Average) is a widely used time-series forecasting model in statistics and machine learning. It is particularly effective for predicting future values based on past observations in datasets where trends exist but strong seasonality may not.

*ARIMA is a statistical model that combines three key components to analyze and forecast time-series data:*

- AutoRegressive (AR) Component – Captures relationships between current and past values.
- Integrated (I) Component – Makes the series stationary by removing trends.
- Moving Average (MA) Component – Captures the relationship between an observation and residual errors from a moving average model.

**Visual Representation:**
You can imagine the ARIMA architecture as a flowchart:

Input Data → Differencing (I) → Stationary Data → AR + MA Model → Output Forecast.

## 🚀 Features
- **Time-Series Forecasting** – Predicts future blood glucose levels based on historical data.
- **Data Preprocessing** – Merges multiple CSV datasets, handles missing values, and formats time-series data.
- **ARIMA Model Tuning** – Optimized **p, d, q** parameters for best forecasting accuracy.
- **Performance Evaluation** – Assesses forecast accuracy using **Mean Absolute Error (MAE) & RMSE**.
- **Scalable Implementation** – Can be adapted for different time-series datasets.

## ⚙️ Requirements
To run this project, install the following dependencies:

### 📌 Required Libraries
- Python 3.8+
- NumPy
- Pandas
- Statsmodels
- Matplotlib
- Seaborn
- SciPy

**📊About The Dataset : HUPA-UCM DIABETES DATASET**

The dataset consists of multiple CSV files, each named with an identifier (e.g., "HUPA0001P.csv" to "HUPA0028P.csv"). These represent individual patient records or data segments.

**Summary of the Data:**

- Time-based dataset: Each row represents a timestamped health measurement.
- Glucose levels: Monitors blood glucose over time.
- Physical activity: Tracks calories burned and steps taken.
- Heart rate: Records fluctuations in heart rate.
- Insulin management: Captures basal insulin rate and bolus insulin delivery.
- Dietary intake: Logs carbohydrate consumption.

## 🙌 Acknowledgments

- This project is inspired by ongoing research in **blood glucose prediction** for Type-1 Diabetes management.  
- Special thanks to **researchers and healthcare professionals** working on improving diabetes forecasting and treatment strategies.  
- Gratitude to the **open-source community** for providing essential libraries such as **TensorFlow, Pandas, Scikit-learn, and Keras**, which made this project possible.  
- Thanks to all contributors who helped refine the model, optimize hyperparameters, and improve performance.  
- Appreciation for **academic research papers and datasets** that provided insights into feature selection and model enhancement.  
- Acknowledgment to the developers of **Jupyter Notebook and Google Colab**, which facilitated interactive model development and experimentation.  



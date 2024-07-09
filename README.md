# **Weather Forecasting with NeuralProphet**  
## Overview
NeuralProphet is a time-series forecasting tool built on top of PyTorch, designed for simplicity and ease of use.
This project focuses on predicting the temperature in Colombo city for the next 900 days. 
By leveraging historical weather data and the capabilities of the NeuralProphet library, the project aims to provide accurate and reliable forecasts that can aid in various applications, from agricultural planning to energy management.

## Installation
To run this project, ensure you have Python installed.

- Use the package manager pip to install the required dependencies:
```python
pip install pystan neuralprophet pandas matplotlib
```
- For Jupyter notebooks:
```python
!pip install pystan neuralprophet pandas matplotlib
```
## Usage
### 1. Clone the Repository:
```python
git clone <repository_url>
cd <repository_name>
```

### 2. Install Dependencies:
- Ensure all required packages are installed as per the installation instructions.

### 3. Run the Project:
- Modify the input data path and configurations as needed. Execute the script to train the NeuralProphet model and generate forecasts.

## Data
- Input Data: Ensure your CSV data file (weatherData.csv) is properly formatted with columns relevant for the NeuralProphet input.

## Model Training
- The NeuralProphet model is trained using historical weather data to learn patterns and seasonal trends. 

## Results
- Forecasting: The model predicts future temperatures (`yhat`) along with upper and lower bounds (`yhat_upper`, `yhat_lower`).

## Visualization
- Plots: Visualizations of forecasted temperatures and components (trend, seasonality) are generated using Matplotlib.

![Plot2](https://github.com/Dhanaa98/Weather-Forecasting-with-NeuralProphet/assets/171159250/0485b8dc-a0cd-4a82-915c-6f64c266fd41)

## Conclusion
In this project, a model to predict the temperature in Colombo city for the next 900 days was developed using the NeuralProphet library. 
The results show promising accuracy and can be utilized for various practical applications. 
Future work can extend this model to include more weather variables and locations, further enhancing its utility and robustness.

For any questions or further assistance, please feel free to contact me.

Dhananjaya Mudunkotuwa  
dhananjayamudunkotuwa1998@gmail.com

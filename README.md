# Seasonality Detection using Continuous Wavelet Transform (CWT)

## Introduction
Welcome to the Seasonality Detection project using Continuous Wavelet Transform (CWT). This project focuses on implementing an algorithm to identify and visualize seasonal patterns within time series data with the help of wavelet.

## Objective
The primary goal of this project is to provide a robust and flexible solution for detecting seasonality in time series data. Leveraging the Continuous Wavelet Transform allows us to handle various types of time series, including those with noise and irregularities. Seasonaliity found can be reviewed in the 'result.pt' tensor. Those information are then used to select the part of dataset where all the information are present.

## Key Features
- **CWT Implementation**: The project includes a well-crafted implementation of the Continuous Wavelet Transform for time series analysis.
- **Seasonality Detection**: The algorithm can effectively detect and visualize seasonal patterns in time series data.
- **Parameter Customization**: Users have the flexibility to adjust parameters to suit the characteristics of their specific datasets.
- **Robust to Noise**: The algorithm is designed to handle noisy and irregular time series data.
- **Data preprocessing**: Handle the dataset in order to select the part where all seasonality are present
- **Forecasting Test**: Using various models can test the performance on forecasting

## Getting Started
To use the seasonality detection algorithm, follow these steps:

1. Clone the repository: https://github.com/FilippoSavini/Seasonality-Algorithm.git
2. Activate the virtual envirnment

## Usage
Follow these steps to incorporate the seasonality detection algorithm into your project:

1. Load your time series data (change the read_csv).
2. Run the seasonality detection algorithm, first with the wavelet transform then with peek detection.
3. Preprocess the time series used in the previous part to select the data.
4. Test on Forecasting


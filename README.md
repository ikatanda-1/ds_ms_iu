
# LSTM Architectures for Stock Price Prediction  A Comparative Study with Hyperparameter Tuning

This repository contains the implementation and analysis for a Master's in Data Science research thesis focused on predicting stock prices using deep learning models. The project explores various architectures, including Vanilla LSTM, Stacked LSTM, Bidirectional LSTM, CNN-LSTM, and Peephole LSTM, for time series forecasting of stock market data.

## Table of Contents
1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Project Structure](#project-structure)
4. [Installation and Setup](#installation-and-setup)
5. [Methodology](#methodology)
6. [Results and Analysis](#results-and-analysis)
7. [Conclusion](#conclusion)
8. [Acknowledgments](#acknowledgments)

## Introduction
This research investigates the effectiveness of deep learning models in predicting stock prices using historical data. The primary objective is to compare the performance of different architectures in capturing temporal patterns and delivering accurate predictions. The dataset comprises historical price data for major technology companies, including Apple, Microsoft, Google, Amazon, and Tesla, covering the period from 2021 to 2023.

## Technologies Used
- Python
- TensorFlow/Keras
- Optuna for hyperparameter optimization
- Matplotlib and Seaborn for visualization
- yFinance for data retrieval
- Pandas and NumPy for data preprocessing

## Project Structure
- `ms_stock_pred_1.ipynb`: Jupyter Notebook containing the entire implementation, from data preprocessing to model evaluation.
- `README.md`: This document.
- `data/`: Directory for raw and preprocessed datasets.
- `models/`: Saved models and configuration files.
- `results/`: Performance metrics and visualizations.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/ikatanda-1/ds_ms_iu.git
   cd ds_ms_iu
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ms_stock_pred.ipynb
   ```

## Methodology
The study employs a range of LSTM-based architectures to analyze historical stock price data. The workflow includes:
1. Data collection using `yFinance`.
2. Preprocessing, including missing value imputation and MinMax scaling.
3. Sequence generation for training and testing.
4. Model training with hyperparameter optimization using Optuna.
5. Evaluation using metrics such as RMSE, MSE, and MAE.
6. Visualization of actual vs. predicted stock prices.

## Results and Analysis
The analysis includes a comparison of the five deep learning architectures in terms of accuracy, execution time, and computational efficiency. Visualizations highlight the models' ability to capture trends and provide insights into their forecasting capabilities.

## Conclusion
The research demonstrates the strengths and limitations of different LSTM-based models in stock price prediction. It offers recommendations for future improvements and potential applications in real-world financial forecasting.

## Acknowledgments
This work was conducted as part of the MSc in Data Science program. Special thanks to the university, supervisors, and contributors who supported this research.


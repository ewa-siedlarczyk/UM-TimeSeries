# Time series forecasting models from small dataset. Project assignment for the Machine Learining classes

Piotr Kőpplinger​, Ewa Siedlarczyk​, Piotr Urbańczyk

## Overview

The goal of this project is to evaluate the performance of several time series forecasting models on a small biological dataset. The dataset captures microbiome samples and their dynamics over time. Our evaluation focuses on two main metrics:
- **Mean Absolute Scaled Error (MASE):** A scale-independent measure of prediction accuracy.
- **Computation Time:** The time required to train and forecast using each model.



## How to Run

1. Clone the Repository:
   ```bash
   https://github.com/ewa-siedlarczyk/UM-TimeSeries.git
   cd UM-TimeSeries
   ```

2. Create a virtual environment and install the dependencies
    ```bash
    python -m venv venv
    source venv/bin/activate  # `venv\Scripts\activate` on windows
    pip install -r requirements.txt
    ```

3. Run jupyter notebook


## Models tested

- ARIMA
- ETS
- RNN
- LSTM
- TCN
- TimesNet
- TFT




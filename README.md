# Cryptocurrency Price Forecasting with AutoTS

This repository contains code that demonstrates the process of downloading cryptocurrency price data and forecasting using the AutoTS library. The project showcases the steps involved in retrieving historical data, processing it, and using AutoTS to forecast cryptocurrency prices.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Data Retrieval](#data-retrieval)
- [Forecasting](#forecasting)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to forecast cryptocurrency prices using historical price data and the AutoTS (Automatic Time Series) library. AutoTS simplifies the process of time series forecasting by automatically selecting and training appropriate forecasting models.

## Prerequisites

### Clone the repository : 

```bash
git clone https://github.com/Mohshaikh23/Cryptocurrency-Price-Prediction-using-AutoTS.git
```

Before running the code, ensure you have the required libraries installed:

- pandas
- yfinance
- autots

You can install them using the following command:

```bash
pip install pandas yfinance autots
```

## Usage

1. Run the code in a Python environment.
2. The code will download historical cryptocurrency price data, process it, and perform forecasting using AutoTS.

## Data Retrieval

The code uses the `yfinance` library to download historical price data for a specific cryptocurrency (e.g., BTC-USD) within a specified date range. The data is collected and processed to prepare it for forecasting.

## Forecasting

AutoTS is employed to automatically select and train appropriate forecasting models based on the input data. The forecasted cryptocurrency prices are then generated using the trained models.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
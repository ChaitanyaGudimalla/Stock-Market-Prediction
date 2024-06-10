# Stock Market Prediction Using RNN-LSTM and KNN

## Project Description
This project aims to predict the future stock prices of the S&P 500 index using two machine learning models: Recurrent Neural Networks (RNN) with Long Short-Term Memory (LSTM) layers and K-Nearest Neighbors (KNN). The project involves data generation, preprocessing, feature selection, training the models, and comparing their performance.

## Dataset
The S&P 500 stock market data from 2013 to 2018 is used for training and testing the models. The dataset avoids the year 2020 to exclude any anomalies due to COVID-19. You can access the dataset from Kaggle [here](https://www.kaggle.com/datasets/camnugent/sandp500).

## Key Features
- **Models**: RNN-LSTM and KNN
- **Features**: Five significant features for stock prediction
- **Evaluation Metrics**: Mean Absolute Error (MAE) and Root Mean Square Error (RMSE)
- **Languages and Libraries**: Python, NumPy, pandas, scikit-learn, and TensorFlow

## Installation

To set up the environment for running the code, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Install dependencies**:
   Make sure you have Python installed. Then, install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the model, execute the following command in your terminal:

```bash
python ML-Project.py
```

This will preprocess the dataset, train the RNN-LSTM and KNN models, and output the prediction results.

## Results

The performance of the models is evaluated based on the RMSE and MAE metrics. The results are compared and analyzed to determine which model performs better in predicting the stock prices.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

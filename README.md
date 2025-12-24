# IF2123-Final Paper
Enhancing Numerical Stability in High-Frequency Trading Algorithms: A Householder QR Decomposition Approach to Rolling Linear Regression

## Dataset
- Source: [High Frequency Crypto Limit Order Book Data (Kaggle)](https://www.kaggle.com/datasets/martinsn/high-frequency-crypto-limit-order-book-data)
- Download (requires Kaggle account and API token):
  ```bash
  kaggle datasets download -d martinsn/high-frequency-crypto-limit-order-book-data -p Dataset
  unzip Dataset/high-frequency-crypto-limit-order-book-data.zip -d Dataset
  ```
- Place the CSVs (e.g., `BTC_1sec.csv`, `ETH_1sec.csv`, etc.) under `Dataset/` so `Source_Code.ipynb` can load them.

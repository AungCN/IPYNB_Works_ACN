# Data Science & Deep Learning Jupyter Notebooks (`IPYNB_Works_ACN`)

A collection of Python Jupyter Notebooks covering machine learning algorithms from scratch, healthcare & epidemiological data analysis, financial stock price time-series forecasting, and traffic flow prediction.

## Notebooks & Contents

- **Recurrent Neural Networks & Financial Forecasting**
  - `AIML_Module7_RNNLSTM_stockprice.ipynb` — Stock price prediction using SimpleRNN, LSTM, GRU, and Bidirectional RNNs with `yfinance` and Keras/TensorFlow.
- **Traffic Flow Prediction (PeMS08)**
  - `trafficflowprediction-pems08-v3.ipynb` & `trafficflowprediction_pems08_v3_1.ipynb` — Deep learning and time-series experiments on the PeMS08 traffic dataset.
  - `BlockDiagram_TrafficFlow.drawio` — Architecture block diagram for the traffic flow prediction pipeline.
- **Epidemiological Data Analysis**
  - `johnhopkincovid19-acn.ipynb` — Exploratory data analysis and visualization of Johns Hopkins University COVID-19 datasets.
- **K-Nearest Neighbors (KNN) Implementations**
  - `diabetes-knn.ipynb` & `knn/` — Diabetes classification using KNN (`diabetes.csv`).
  - `iris-datasetknn.ipynb`, `iris-knn-manual-2.ipynb`, `iris-knn-manual-sorted-mar2025.ipynb` — Manual and scikit-learn KNN implementations on the Iris dataset.

## Setup & Usage

1. Clone the repository and install required packages:
   ```bash
   git clone https://github.com/AungCN/IPYNB_Works_ACN.git
   cd IPYNB_Works_ACN
   pip install -r requirements.txt
   ```
2. Start Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```

## License

This project is licensed under the [MIT License](LICENSE).

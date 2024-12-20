# MarketMaven: AI-Powered Stock Price Prediction App
**MarketMaven** is a Streamlit-based application designed to revolutionize stock price prediction by experimenting with advanced machine learning and deep learning techniques. Leverage cutting-edge models like Support Vector Machines (SVM), Long Short-Term Memory Networks (LSTM), and Multi-Head Attention to gain insights and make informed predictions about stock prices.

<p align="center">
    <img width="50%" alt="Streamlit demo app 1" src="./assets/market_marven.webp">
</p>

## Features
- **Interactive Stock Data Visualization**:
  - Fetch and visualize historical stock prices with dynamic charts.
  - Analyze trends and patterns to inform your predictions.

- **Advanced Model Experimentation**:
  - **Machine Learning**: Explore models like Support Vector Machines (SVM), Random Forests, and Gradient Boosting.
  - **Deep Learning**: Experiment with state-of-the-art models like LSTM, GRU, and Multi-Head Attention.

- **Customizable Parameters**:
  - Adjust model parameters such as window sizes, epochs, and learning rates to optimize predictions.

- **Real-Time Insights**:
  - Visualize predicted stock trends against actual prices to assess model performance.

---

## Getting Started

### Prerequisites
- Python 3.8 or later
- Required libraries (install via `requirements.txt`):
  - Streamlit
  - Pandas
  - Numpy
  - Scikit-learn
  - TensorFlow or PyTorch
  - Matplotlib
  - yfinance

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/marketmaven.git
    cd marketmaven
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the application:
    ```bash
    streamlit run app.py
    ```

### Usage
1. Launch the app and enter the stock ticker symbol (e.g., AAPL for Apple Inc.).
2. Choose the prediction model:
    - SVM: For a quick and robust machine learning approach.
    - LSTM: For sequential time-series data analysis.
    - Multi-Head Attention: For capturing long-term dependencies and trends.
3. Customize model parameters and visualize predictions.
4. Compare the predicted stock prices with historical data.


### Project Structure

```bash
marketmaven/
├── data/                   # Sample datasets or downloaded stock data
├── models/                 # Pre-trained or custom machine learning models
├── app.py                  # Main Streamlit app
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
```


### Future Enhancements
Incorporate reinforcement learning for dynamic portfolio optimization.
Add more deep learning architectures like Transformers.
Integrate news sentiment analysis to augment prediction accuracy.

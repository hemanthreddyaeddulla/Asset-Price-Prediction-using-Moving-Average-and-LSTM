### Asset Price Prediction Using Moving Average and LSTM

---

#### **Project Description**
This project implements a robust solution for predicting asset prices using a combination of Moving Averages and Long Short-Term Memory (LSTM) models. It includes tools for data fetching, preprocessing, visualization, model training, and deployment through a web-based interface. The application predicts stock prices, allowing users to input a stock ticker and view predictions alongside historical data trends.

---

#### **Features**
- **Data Fetching**: Automatically retrieves historical stock price data using the `yfinance` API.
- **Preprocessing**: Incorporates Moving Average calculations for smoothing and trend analysis.
- **Model**: Employs an LSTM neural network for accurate time-series forecasting.
- **Visualization**: Displays historical data, predictions, and moving average trends through graphical plots.
- **Deployment**: Includes a Streamlit-based web interface for user-friendly interactions.

---

#### **How to Use**
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/hemanthreddyaeddulla/Asset-Price-Prediction-using-Moving-Average-and-LSTM
   ```

2. **Install Dependencies**:  
   Ensure Python is installed, then install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Web App**:  
   Start the Streamlit application to interact with the model:  
   ```bash
   streamlit run web_stock_price_predictor.py
   ```

4. **Train the Model (Optional)**:  
   Modify and execute the Jupyter Notebook for custom training:  
   ```bash
   jupyter notebook stock_price_prediction_using_moving_average_and_LSTM.ipynb
   ```

---

#### **File Descriptions**
1. **`Asset_Price_Model.keras`**: Pre-trained LSTM model for asset price predictions.
2. **`stock_price_prediction_using_moving_average_and_LSTM.ipynb`**: Jupyter Notebook containing data processing, model training, and evaluation steps.
3. **`web_stock_price_predictor.py`**: Streamlit-based script for deploying the prediction model as a web application.

---

#### **Applications**
- **Investors**: Gain insights into stock price trends and make informed investment decisions.
- **Researchers**: Utilize this model as a base for exploring advanced forecasting techniques.
- **Developers**: Extend the application to include more sophisticated features such as additional technical indicators or model ensembles.

---

#### **Pros**
- Seamless integration of Moving Averages and LSTM ensures both short-term and long-term trend detection.
- Simple deployment process using Streamlit, making it accessible to non-technical users.
- Open-source and modular, enabling community contributions and customizations.

---

#### **Cons**
- Limited to historical price-based predictions; doesn't factor in external economic or market data.
- Performance may degrade for volatile stocks with irregular patterns.
- Dependent on `yfinance` API, which may introduce delays or limitations in data fetching.

---

#### **Future Enhancements**
- **Incorporate Sentiment Analysis**: Integrate news and social media sentiment to improve forecasting accuracy.
- **Multi-Asset Support**: Extend the app to analyze and predict multiple stocks simultaneously.
- **Enhanced Models**: Experiment with Transformers or hybrid architectures for better time-series predictions.
- **Automated Alerts**: Implement email or SMS notifications for significant market changes.

---

#### **Dependencies**
- Python 3.11.5
- Libraries:
  - `tensorflow`, `keras`: For building and running the LSTM model.
  - `yfinance`: To fetch historical stock data.
  - `streamlit`: For deploying the interactive web interface.
  - `matplotlib`, `pandas`, `numpy`: For data processing, manipulation and visualization.

---

#### **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

# Stock Market Forecast with LLM

## Overview
This project combines traditional technical analysis with artificial intelligence to provide comprehensive stock market predictions and analysis. The system processes real-time market data from major tech stocks (AAPL, MSFT, GOOGL, AMZN, TSLA) and generates actionable insights through:

### What You Get:
1. **Price Predictions**
   - Next-day price forecasts
   - Trend direction indicators
   - Confidence metrics for predictions

2. **Technical Analysis Visualization**
   - Interactive price charts
   - Moving averages (20-day and 50-day)
   - RSI (Relative Strength Index) indicators
   - Overbought/Oversold signals

3. **AI-Powered Insights**
   - Market sentiment analysis
   - Risk level assessment
   - Trading recommendations (Buy/Hold/Sell)
   - Automatic pattern recognition

4. **Performance Metrics**
   - Current price vs predicted movement
   - Technical indicator status
   - Sentiment analysis scores
   - Risk assessment levels

## Project Structure

### Data Fetching and Processing
- Uses `yfinance` to fetch real-time stock data
- Processes historical data for technical analysis
- Handles data cleaning and formatting for analysis

### Technical Analysis
- Calculates Moving Averages (20-day and 50-day) for trend identification
- Implements Relative Strength Index (RSI) for overbought/oversold signals
- Processes price movements and volume data

### LLM Integration
- Utilizes OpenAI's API for sentiment analysis
- Processes financial news and market sentiment
- Incorporates AI-driven insights into the analysis

### Visualization Components
- Creates interactive price charts with technical indicators
- Displays RSI analysis with overbought/oversold zones
- Visualizes predicted price movements
- Shows sentiment analysis results

## Features
- Stock data fetching using yfinance
- Technical analysis with moving averages and RSI
- Price prediction using historical data
- Sentiment analysis integration
- Visualization of stock trends and indicators

## Key Functions
- `fetch_stock_data()`: Retrieves historical stock data
- `calculate_technical_indicators()`: Computes technical analysis metrics
- `analyze_with_llm()`: Processes text data using LLM
- `analyze_sentiment_batch()`: Batch processes sentiment analysis
- `plot_predictions()`: Creates visualization of analysis results

## Dependencies
- Python 3.x
- pandas: Data manipulation and analysis
- yfinance: Stock data retrieval
- numpy: Numerical computations
- scikit-learn: Data preprocessing
- matplotlib: Data visualization
- seaborn: Statistical data visualization
- openai: LLM integration

## Setup and Usage
1. Clone the repository
2. Install required dependencies
3. Set up OpenAI API key in .env file
4. Run the Jupyter notebook

## Environment Setup
Create a .env file with:
```env
OPENAI_API_KEY=your_api_key_here

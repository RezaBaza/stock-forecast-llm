# Stock Market Forecast with LLM

This project uses Python and Large Language Models to analyze and forecast stock market movements. The system analyzes data from major tech stocks including AAPL, MSFT, GOOGL, AMZN, and TSLA.

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
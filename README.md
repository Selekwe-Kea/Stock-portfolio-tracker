# Stock-portfolio-tracker
Stock Portfolio Tracker
A web application for tracking and managing your stock portfolio, built with Python and Flask.

Features
Dashboard: View portfolio summary, performance charts, and recent transactions
Portfolio Management: Add/withdraw cash, buy/sell stocks
Transaction History: Track all portfolio transactions with filtering options
Portfolio Analysis: Analyze portfolio performance, diversification, and risk metrics
Stock Search: Search for stocks to add to your portfolio
Tech Stack
Backend: Python, Flask
Frontend: HTML, CSS, JavaScript, Bootstrap 5
Data Visualization: Matplotlib
Data Processing: Pandas, NumPy
External APIs: Alpha Vantage for stock data
Installation
Clone the repository:
git clone https://github.com/yourusername/stock-portfolio-tracker.git
cd stock-portfolio-tracker
Install dependencies:
pip install flask matplotlib numpy pandas requests tabulate
Get an Alpha Vantage API key:

Sign up at Alpha Vantage
Set the API key as an environment variable:
export ALPHAVANTAGE_API_KEY=your_api_key
Run the application:

python app.py
Open your browser and navigate to:
http://localhost:5000
Usage
Add Cash: Click "Add Cash" button to deposit funds into your portfolio
Buy Stocks: Search for stocks, then use the buy form to purchase shares
Sell Stocks: Select one of your holdings to sell shares
View Performance: Check the Analysis page for detailed performance metrics
Track Transactions: View your transaction history on the Transactions page
Project Structure
app.py: Main Flask application
core/: Core functionality
stock_tracker.py: Portfolio tracking logic
utils.py: Utility functions for data processing and visualization
static/: Static assets (CSS, JavaScript)
templates/: HTML templates
License
MIT

Acknowledgments
Alpha Vantage for providing stock market data API
Bootstrap for the UI components
Flask for the web framework

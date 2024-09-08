# Investment Portfolio Analytics

This repository contains a Python-based tool for analyzing stock investment portfolios. It uses `pandas` and `plotly` to generate insightful visualizations from portfolio data, including investment over time, stock allocation, and performance metrics.

## Features

- **Cumulative Investment and P&L Over Time**: A line chart visualizing the total amount invested and the cumulative profit/loss over time.
  
- **Stock Allocation by Value**: A pie chart representing the distribution of your portfolio based on the current value of each stock.

- **Unrealized Profit & Loss**: A bar chart showing the unrealized profit or loss per stock, color-coded for positive and negative P&L.

- **Total Quantity Held per Stock**: A bar chart displaying the total quantity of each stock held in your portfolio.

- **Buy Value vs Unrealized P&L**: A stacked bar chart comparing the total buy value and unrealized profit/loss for each stock.

- **Performance by Holding Period**: A scatter plot showing how long you held each stock (in days) versus the unrealized P&L.

- **P&L Percentage by Stock**: A bar chart illustrating the percentage profit or loss relative to the amount invested for each stock.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/INVESTMENT-PORTFOLIO-ANALYTICS.git
   cd INVESTMENT-PORTFOLIO-ANALYTICS
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place your portfolio data in a CSV file named `data.csv`. The required columns are:
   - `Stock name`: Name of the stock
   - `Buy date`: Date when the stock was purchased (format: DD-MM-YYYY)
   - `Closing date`: Date when the stock was closed/sold (or left blank if not sold)
   - `Buy value`: The value of the stock at the time of purchase
   - `Closing value`: The value of the stock at the time of closing (if applicable)
   - `Quantity`: Number of shares purchased
   - `Unrealised P&L`: The profit or loss for the stock if it hasn't been sold yet
   - `Remark`: (Optional) Any additional remarks

2. Run the Jupyter Notebook or Python script to generate the visualizations:
   ```bash
   jupyter notebook Investment_Analytics.ipynb
   ```

## Example Visualizations

- **Amount Invested vs Total P&L Over Time**
  
  ![Cumulative Invested and P&L](images/invested_vs_pnl.png)

- **Stock Allocation by Value**

  ![Stock Allocation](images/stock_allocation.png)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

# Stock Price Analysis

## Overview
This project analyzes stock price movements using Python. It loads historical stock data from a CSV file, processes the data, and visualizes trends and volatility using various statistical methods.

## Features
- Load and preprocess stock price data
- Visualize stock price movements over time
- Calculate and plot 50-day and 200-day simple moving averages (SMA)
- Compute daily returns to analyze stock volatility
- Generate basic statistical insights

## Requirements
To run this project, you need the following Python libraries installed:

```bash
pip install pandas matplotlib numpy
```

## Usage
1. **Download or collect stock price data** in CSV format.
2. **Modify the `file_path` variable** in `stock_analysis.py` to point to your CSV file.
3. **Run the script**:

```bash
python stock_analysis.py
```

4. The script will generate and display:
   - Stock price movement chart
   - Moving averages (50-day and 200-day) chart
   - Stock price volatility chart
   - Basic statistical insights

## Expected Output
- **Stock Price Movement**: A graph showing the closing price trend.
- **Moving Averages**: A graph with stock price along with 50-day and 200-day SMAs.
- **Volatility Analysis**: A graph displaying daily returns.
- **Statistical Summary**: Descriptive statistics of stock prices.

## File Structure
```
/stock_price_analysis
│── stock_analysis.py  # Main script for analysis
│── stock_data.csv     # Sample dataset (Replace with actual data)
│── README.md          # Documentation
```

## References
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [NumPy Documentation](https://numpy.org/)

## License
This project is open-source and available under the MIT License.

---
For any queries or improvements, feel free to contribute! 🚀


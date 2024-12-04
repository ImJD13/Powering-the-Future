# Investment Banking & Renewable Energy Price Prediction

This project investigates the profitability of investing in renewable sources (such as lithium, solar, and ESG) within a commodities portfolio. It leverages historical price data of energy-related stocks and ETFs and uses a Linear Regression model to predict future prices.

## Project Overview
- **Objective**: Analyze the price trends and profitability of renewable energy stocks (e.g., Lithium, Solar) compared to traditional energy sources (e.g., Oil).
- **Focus**: Use investment banking concepts and financial tools (e.g., green bonds) to understand the profitability potential of these sources.
- **Machine Learning Component**: Linear Regression model to predict future prices based on historical data.

## Files and Directories
- **`data/`**: Contains CSV files with historical stock data (price history, adjusted close).
- **`notebooks/`**: Jupyter notebooks containing data analysis, model training, and predictions.
- **`requirements.txt`**: Lists the dependencies for this project.
- **`README.md`**: This file.

## Getting Started

### Prerequisites
1. **Install Python**: Ensure Python 3.x is installed.
2. **Install Dependencies**: The project requires several Python packages. To install them, run the following command:
    ```
    pip install -r requirements.txt
    ```

### Running the Code
1. **Clone the repository**:
    ```
    git clone https://github.com/Im-JD13/your-repo-name.git
    cd your-repo-name
    ```

2. **Download Data**: The project fetches stock price data using the Alpha Vantage API. Ensure that you have an API key for Alpha Vantage (you can get one at [Alpha Vantage](https://www.alphavantage.co)) and set it up in your script.

3. **Run the Analysis**: Open the Jupyter Notebook and execute the cells sequentially:
    ```
    jupyter notebook
    ```

4. **ML Model**: The project includes a Linear Regression model to predict future stock prices based on historical data. After running the analysis, you will see visualizations and performance metrics (e.g., Mean Squared Error).

## Contributing

Feel free to fork the repository, make changes, and create a pull request for any improvements or new features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

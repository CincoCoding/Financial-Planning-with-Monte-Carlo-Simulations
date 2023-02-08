# Financial Planning with Monte Carlo Simulations

![planner](/Images/financial-planner.png)

## Financial Planning with Monte Carlo Simulations
This project aims to provide an overview of a personal finance planner. The project uses data from cryptocurrency and shares to get the value of the user's portfolio. The project also uses Monte Carlo simulations to forecast the future value of the portfolio.

## Requirements
The following libraries are required to run this project:
* os
* requests
* pandas
* dotenv
* alpaca_trade_api
* MCForecastTools
* json


## Part 1 - Personal Finance Planner
This section of the project is focused on collecting data on the user's portfolio and evaluating its value. The following data is collected:

* The current price of Bitcoin and Ethereum
* The value of the user's Bitcoin and Ethereum holdings
* The current price of AGG and SPY
* The value of the user's AGG and SPY holdings
* The total value of the portfolio is compared to an emergency fund (three months' worth of income). The user is notified if their emergency fund is sufficient or if additional funds are needed.

## Part 2 - Monte Carlo Simulations
This section of the project uses Monte Carlo simulations to forecast the future value of the user's portfolio. The Monte Carlo simulations are performed on the portfolio's assets to determine its future value. The results of the simulations are plotted and displayed for the user to review.

![monte carlo sim](/Images/monte-carlo.png)

## How to Run the Project
To run the project, you must have all the required libraries installed. You will also need to set up a .env file with your Alpaca API key and secret key. Once these requirements are met, run the code in a Jupyter Notebook or in your preferred development environment.

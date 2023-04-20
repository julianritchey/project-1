# Project 1 - Portfolio tracker

## Investor's dream application

### Goal objectives and purpose
> <p align="justify"> Develop a real-time portfolio tracker that performs the following functions that displays historic and existing investments from multiple exchanges.Stores historic and existing investments in a local database.Provides forecasting models for various investment assets. Displays data in tabular and graphical formats.Portofolio planner, forecasting, and simulation of portfolios with visualization using interactive graphs, charts, plots  </p>
> 
### Dream big, Questions to be answered, Preparation, and execution

> <p align="justify"> How can we diversify an investor’s portfolio such that it can be profitable and has stocks with a security worth investing? How do we present information to an investor looking to diversify their stock portfolio, maximizing their profits such that they can study the company and make an informed decision before investing?
One of the answers to this question is forecasting the stock’s closing price. However, it is very difficult to predict something that depends on the future which is uncertain and unpredictable. Stock data is also very volatile. As you can see in the figure below, the stock closing price trends look like that of a random walk. </p>
>  
> <p align="justify"> ### MonteCarlo Simulations ###
The program will read a CSV file containing our portfolio data. Based on this
data, a new CSV report will be generated using live market value to indicate
our current holding performance using the IEX API.

The program will be installable using `pip`, and requires a `setup.py`
file. When installed, a binary will be added to the Python path which can be
invoked from anywhere on the filesystem.</p>

### Investor's dream's features ###
> <p align="justify"> Every investor's million dollar question
> 1. How can an investor compare multiple simulated portfolios to determine their ideal investment portfolio?
> 2. How can an investor make the most money with the least amount of risk? Which asset mix can provide the strongest portfolio given current market conditions?
> 3. In what ways can an investor visualize their investment planning data?
> 4. How can an investor make the most money with the least amount of risk? Which asset mix can provide the strongest portfolio given current market conditions? In what ways can an investor visualize their investment planning data?

### Investor's dream's features ###
> <p align="justify"> With Investor’s Dream it is possible to add multiple portfolios, save them in a database and run the simulation for each portfolio individually.

<p align="justify"> Calculate Daily Returns,Cumulative Returns,Calculate Beta, Sharpe Ratios, Run Monte Carlo Simulation Visualizuation of investments with interactive plots.
 
> <p align="justify"> The asset mix can provide the strongest portfolio given current market conditions

### Resources, technology emplo ###

<p align="justify"> 

> APIS: Historical Data:Yahoo Finance API,Alpaca API,Current Investments,Kucoin crypto exchange API 
Coin API,Alpha Vantage API   

> - Data Cleaning with Pandas Set data hierarchy according to the requirements
Cleaning, and filtering of data, renaming columns
Easier to clean data using one constant source, e.g. yfinance library
Concatenating different Dataframes

> - Technical issues: As with any technology platform, Starbucks' mobile app and digital systems can sometimes experience technical glitches or outages that can frustrate customers.
> 

### Resources, technoloy employed in development of app  ###

> <p align="justify"> To analyze the results of a Monte Carlo simulation, financial analysts often use metrics such as Sharpe ratios, standard deviations, and correlations. The Sharpe ratio, for example, measures the excess return of a portfolio relative to the risk-free rate, divided by its standard deviation. The standard deviation measures the degree of variability of the portfolio's returns, while correlations measure the degree to which the returns of different assets move together.

### Running the application ###

Clone this repository: git clone #https://github.com/julianritchey/project-1
Install the required dependencies: pip install -r requirements.txt
Create the database: python create_db.py
Run the application: python app.py
Open your browser and go to https://fintech1.richedev.com/

### Data conclusions  ###
Investor's dream's application's analysis
> <p align="justify"> In finance, Monte Carlo simulations are often used to analyze the risk and return of a portfolio of assets. The technique involves creating a model of the portfolio that takes into account the historical performance of the assets, as well as their expected future returns, volatility, and correlations with one another.

### Dream doesn't cost anything ###
Humble beginnings, abundant future
> <p align="justify"> 



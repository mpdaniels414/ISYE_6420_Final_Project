# ISYE 6420 Final Project: Bayesian Options Pricing

## Overview
This project explores the application of Bayesian methodologies in options pricing, specifically comparing the Metropolis-Hastings (MH) algorithm with the traditional Black-Scholes (BS) model. By analyzing the stocks META, HD (Home Depot), and AAPL (Apple), this study demonstrates the potential and limitations of Bayesian methods in financial modeling. The project offers insights into the stability, volatility, and adaptability of Bayesian approaches to pricing options in dynamic market conditions.

## Project Goals
- Evaluate the applicability of Bayesian methods for options pricing.
- Compare the Metropolis-Hastings algorithm to the Black-Scholes model.
- Analyze market behavior of three stocks: META, HD, and AAPL.
- Identify potential advantages of Bayesian methodologies in financial forecasting.

## Data Description
The dataset, obtained from Yahoo Finance, includes daily closing prices for META, HD, and AAPL over one year.  
- **Strike Price:** Determined using a 10-day moving average of closing prices.  
- **Expiration Period:** Set uniformly at 90 days for all options.  
- **Risk-Free Rate:** A constant annual return of 5% was used.  

The dataset has been preprocessed for compatibility with the implemented models.

## Project Files
1. **Final_Project.ipynb**  
   - Contains the implementation of the Metropolis-Hastings algorithm for Bayesian options pricing.
   - Includes the Black-Scholes model for comparison.
   - Performs detailed volatility analysis and visualizations.

2. **ISYE-6420 Final Project.pdf**  
   - Provides an in-depth write-up of the project, including methodology, data details, results, and future directions.

## Methodology
- **Black-Scholes Model:** Utilized for theoretical options pricing with a vectorized implementation.  
- **Metropolis-Hastings Algorithm:** Simulates stock price paths under varying market conditions, leveraging Bayesian principles.  
- **Volatility Estimation:** Calculated using frequentist methods, with plans for future Bayesian implementations.  

## Results
- The MH model showed less volatility than expected, closely mirroring the BS model's price estimates.
- No consistent pattern emerged in how the MH model priced options relative to the BS model.
- The study highlights the potential of Bayesian approaches for stable and reliable options pricing.

## Future Directions
- Explore Bayesian volatility estimation using an inverse gamma distribution for posterior variance analysis.
- Develop adaptive models for real-time financial forecasting.
- Integrate computationally efficient Bayesian methods to enhance model scalability.

## Requirements
- Python 3.9 or higher
- Libraries: NumPy, SciPy, Matplotlib, Pandas

## How to Run
1. Clone this repository.
2. Ensure all dependencies are installed.
3. Open and run `Final_Project.ipynb` in Jupyter Notebook or a similar environment.

## References
- [Yahoo Finance](https://finance.yahoo.com)
- [Black-Scholes Model Implementation](https://www.codearmo.com/python-tutorial/options-trading-black-scholes-model)
- Additional references are listed in the **ISYE-6420 Final Project.pdf** file.

---

This project is a comprehensive exploration of Bayesian options pricing methodologies, showcasing their potential to enhance financial modeling practices.

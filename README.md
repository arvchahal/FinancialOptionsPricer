# Financial Options Pricer

**Disclaimer:** This software is for educational purposes only. It should not be used for making financial or investment decisions. The author is not responsible for any financial loss caused by using this software. Always consult with a certified financial advisor before making investment decisions.

**Author:** Arnav Chahal  
**Institution:** Vanderbilt University

This is a financial options pricer used to price the theoretical value of options contracts.

## Features

- **Black-Scholes Model:** Implementation of the Black-Scholes Model for calculating the theoretical price of European call and put options.
- **Monte Carlo Simulation:** Monte Carlo simulation used for estimating the price of an option.
- **Binomial Options Pricing Model:** Implementation of the Binomial Options Pricing Model that computes the price of an option by creating a binomial tree of potential future asset prices and working backwards from the end of the tree to the present.

## Dependencies

- Boost libraries for mathematical calculations.
- C++ Standard Template Library (STL).

## Building the Project

1. Clone the repository.
2. Navigate to the project directory.
3. Compile the project with your preferred C++ compiler, ensuring the Boost libraries are included. You might have to download the Boost libraries and edit the CMakeLists.txt in order for it to run on your computer.

**Note:** This project was written in C++ and requires a C++ compiler to run. It was developed and tested using the Clang compiler, but should work with other C++ compilers as well.

## Usage

Once compiled, you can use the various classes to compute option prices. Note that the parameters for the models, such as the stock price, volatility, strike price, risk-free rate, and time to maturity, must be set according to your requirements. Additionally, this only works for European options and does not account for dividends earning stocks.

## License

This project is licensed under the MIT License.

**Additional Notes:**  
Have fun and play around with the code!

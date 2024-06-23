Heston’s Stochastic Volatility Model Documentation

Project Overview
This project aims to estimate the parameters of the Heston model for option pricing using the method of moments. The Heston model accounts for stochastic volatility, offering a more accurate representation of market dynamics compared to the Black-Scholes model, which assumes constant volatility. The project's main steps include deriving and testing the option pricing formulas for the Heston model and comparing them with the Black-Scholes model using historical data.

Research Paper Summary
The research paper "Estimating Option Prices with Heston’s Stochastic Volatility Model" focuses on deriving and testing option pricing formulas for the Heston model, which describes the asset’s volatility as a stochastic process. The paper uses historical option data to compare the estimated option prices from the Heston model and the Black-Scholes model, demonstrating that the Heston model provides more accurate option pricing estimates.

Key Points

Heston Model: A stochastic volatility model where the asset price and its volatility follow random Brownian motion processes.
Euler Discretization: Used to discretize the continuous-time Heston model for practical parameter estimation
Method of Moments: Employed to estimate the parameters of the Heston model from historical asset price data.
Comparison with Black-Scholes: The Heston model's option pricing estimates are compared with those of the Black-Scholes model, showing the Heston model's superior accuracy.

Conclusion
This project demonstrates the process of estimating parameters for the Heston stochastic volatility model using the method of moments. The estimated parameters can then be used to price European call options more accurately than traditional models like Black-Scholes. This approach leverages the computational power of Python and numerical optimization techniques to fit the model to historical asset price data.

References
-Estimating Option Prices with Heston’s Stochastic Volatility Model
-Python documentation and numpy library


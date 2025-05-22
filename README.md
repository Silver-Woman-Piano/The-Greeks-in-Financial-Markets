# The-Greeks-in-Financial-Markets

📘 Greeks Visualization – Quantitative Finance Exploration
This project explores the Greeks—key sensitivity measures in options pricing—using Python.
It provides a mathematical and visual analysis of how Delta, Gamma, Vega, Theta, and Rho behave as the underlying asset price varies.

🧮 Features
Compute and plot option price and Greeks (Delta, Gamma, Vega, Theta, Rho)

Use a basic Black-Scholes model (assumes a european_option class is defined)

Visualize how these sensitivities change with the underlying asset price

🧠 Objective
To offer an educational and intuitive introduction to the Greeks, aimed at students and finance enthusiasts interested in quantitative finance and options risk management.

📦 Requirements
bash
Copier
Modifier
pip install numpy matplotlib
You also need to define or import a european_option class or function that provides methods:

python
Copier
Modifier
option.value()
option.delta()
option.gamma()
option.vega()
option.theta()
option.rho()
🚀 Run the code
bash
Copier
Modifier
python greeks_visualization.py
📊 Output
Line plot of the call option's value across a range of underlying prices

Subplots showing how each Greek behaves with respect to the underlying asset

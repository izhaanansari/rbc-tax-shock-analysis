# Stochastic Tax Shock Analysis via RBC Model

Built a Real Business Cycle (RBC) model to analyze how stochastic tax shocks propagate through a macroeconomy. Using FRED data to calibrate tax-to-GDP ratios, the model derives key equilibrium conditions and simulates dynamic responses to fiscal disturbances.

## What the Model Does
- Derives Euler equations, government budget constraint, capital evolution, production function, and market clearing conditions
- Computes steady-state equilibria using a python library called linearsolve
- Generates impulse response functions (IRFs) showing how capital, consumption, investment, output, and fiscal surplus respond to a tax shock
- Compares IRF behavior across multiple tax persistence values (ρ = 0.00001, 0.8, 0.9)

## Tools & Data
**Tools:** Python, linearsolve, pandas, NumPy, matplotlib  
**Data Source:** Federal Reserve Economic Data (FRED) — federal tax receipts & GDP

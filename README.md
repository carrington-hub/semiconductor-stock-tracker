# Semiconductor Stock Price Tracker

A Python tool that tracks and visualizes 1-year price performance 
of major semiconductor companies using live market data.

## Companies Tracked
| Ticker | Company |
|--------|---------|
| NVDA | NVIDIA |
| TSM | TSMC |
| AMD | AMD |
| INTC | Intel |
| AMAT | Applied Materials |
| TXN | Texas Instruments |

## What It Does
- Pulls 1 year of live stock price data using yfinance
- Normalizes prices to a common baseline for fair comparison
- Calculates annual return and volatility for each company
- Generates two visualizations — normalized performance chart 
  and annual return bar chart
- Prints a formatted summary table to the terminal

## Skills Demonstrated
- Python — NumPy, Pandas, Matplotlib, yfinance
- Data analysis and visualization
- Financial modeling concepts — Geometric Brownian Motion, 
  return calculation, volatility measurement
- Object-oriented data organization using dictionaries

## How to Run

Install dependencies:
pip install numpy pandas matplotlib yfinance

Run the script:
python semiconductor_tracker.py

## Sample Output
![Semiconductor Tracker Chart](semiconductor_tracker.png)

## Background
Built as part of my self-directed semiconductor engineering 
education while completing pre-engineering coursework at 
Lee College (Baytown, TX) in preparation for transfer to 
an electrical engineering program with a semiconductor focus.

U.S. Air Force veteran — 6 years as EC-130 Airborne 
Maintenance Technician. Transitioning from maintaining 
avionics and electronic warfare systems to designing 
the semiconductor technology that powers them.

## Author
Carrington Davis
Electrical Engineering Student | Semiconductor Focus | USAF Veteran
linkedin.com/in/carrington-davis-b58b66276

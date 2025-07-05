# Historical Value-at-Risk (VaR) Simulation

This project implements a Historical Simulation approach to estimate Value-at-Risk (VaR) for a portfolio of stocks using Python. It includes data retrieval, portfolio construction, P&L simulation, VaR calculation, violation analysis, and interactive visualizations.

---

## Features

- Downloads historical stock data using `yfinance`
- Computes portfolio returns from multiple assets
- Estimates 95% and 99% Historical VaR
- Detects and visualizes VaR violations
- Interactive Plotly visualizations

---

## Concepts Used

- Log Returns & Portfolio Aggregation  
- Historical Simulation for VaR  
- Violation detection & evaluation  
- Plotly for interactive plotting  

---

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/var-simulation.git
cd var-simulation

# (Optional) Create a virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
````

---

## Usage

```bash
python var_simulation.py
```

Or run the notebook (if applicable):

```bash
jupyter notebook VaR_Simulation.ipynb
```

---

## Evaluation Metrics

* Violation Rate (actual vs. expected)
* Optional: Kupiec’s Proportion of Failures test

---

## Requirements

* `yfinance`
* `numpy`
* `pandas`
* `scipy`
* `plotly`
* `matplotlib`

---

## Contributing

Contributions, suggestions, and improvements are welcome!
Please open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# BBVA Portfolio Optimization

Reproducible portfolio optimization for my BBVA funds using Python (`PyPortfolioOpt`) with proxy ETFs for live market data.

---

## 🧭 Project Structure
```
bbva-portfolio-optimization/
├── data/                      # Input CSVs (fund list, weights)
├── notebooks/                 # Jupyter notebooks
├── plots/                     # Exported charts
├── requirements.txt           # Python dependencies
└── README.md                  # Project overview
```

---

## ⚙️ How to Run

### ▶️ In GitHub Codespaces

1. Open the repo → **Code → Codespaces → Create codespace on main**

2. Install libraries:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `notebooks/01_portfolio_optimization.ipynb`

---

## 🧠 Objective

Use **Modern Portfolio Theory** to optimize my BBVA portfolio:

- Compute expected returns, volatility, and correlation  
- Compare current vs optimized weights  
- Plot the **Efficient Frontier**  
- Assess diversification and risk contribution

---

## 🔮 Next Steps

- Add constraints (max/min weight)  
- Run backtests  
- Perform factor analysis  
- Automate monthly updates

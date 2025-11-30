# BSM Option Pricing & Greeks Calculator 🧮📈

**Author:** Naman Choudhary (LIGHTARK)  
**Repo:** LIGHTARK-2903/BSM-Option-Pricing  

---

## 🔹 What is this  

This repository contains a simple but fully functional tool to compute theoretical prices and “Greeks” (Delta, Gamma, Vega, Theta, Rho) of European-style stock options using the classic Black–Scholes–Merton model (BSM).  

Using standard inputs — underlying stock price, strike price, implied volatility, time to maturity, risk-free rate — the model returns fair option price and risk-sensitivities that help in portfolio analysis, risk management and option pricing studies. :contentReference[oaicite:1]{index=1}

---

## 🔧 Features

- Calculation of Call and Put option prices using BSM formula  
- Outputs all major Greeks: Delta, Gamma, Vega, Theta, Rho  
- Flexible input fields (spot price, strike, volatility, expiry, interest rate)  
- Option chain / scenario-analysis capable via Excel / Jupyter Notebook  
- Exportable to CSV / Excel for further analysis  
- Ideal for students, traders, or anyone interested in derivatives pricing

---

## 📂 Repository Structure

| File / Folder | Purpose |
|--------------|---------|
| `BSM Option Pricing and Greek Values.xlsx` | Excel-based calculator — user-friendly spreadsheet version |
| `BSM_Option_Pricing_and_Greeks_LightarkFinance.ipynb` | Jupyter Notebook implementation (Python) |
| `requirements.txt` | Dependencies required for Python version |
| `all_greeks.png` | Sample output graphs / visuals (if any) |
| `README.md` | This file |

---

## 🚀 How to Use

### Option A — Excel
1. Open `BSM Option Pricing and Greek Values.xlsx`  
2. Fill in the inputs: Spot Price, Strike Price, Volatility (%), Time to Expiry (in years), Risk-free Rate (%)  
3. Results (Call / Put price + Greeks) will auto-update via inbuilt formulas  

### Option B — Python (Notebook)
```bash
git clone https://github.com/LIGHTARK-2903/BSM-Option-Pricing.git  
cd BSM-Option-Pricing  
pip install -r requirements.txt  
jupyter notebook BSM_Option_Pricing_and_Greeks_LightarkFinance.ipynb  

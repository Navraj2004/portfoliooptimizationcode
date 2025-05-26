## 📊 Portfolio Optimization using Fuzzy Set Logic and Whale Optimization Algorithm

---
### ▶️ How to Run the Project

You can easily run this project using **Google Colab** without any local setup. Follow these steps:

1. Go to [Google Colab](https://colab.research.google.com/)
2. Click on **"New Notebook"**
3. Copy the complete code from this repository
4. Paste it into the Colab notebook
5. Click on **Runtime > Run all** to execute all cells

Make sure you have an internet connection, as some libraries may need to be installed using `!pip install` commands within the notebook.

> ✅ No need to install anything locally – it's all cloud-based!

### 🔍 Overview

This project focuses on optimizing a stock portfolio using a hybrid approach that combines **Fuzzy Set Logic** and the **Whale Optimization Algorithm (WOA)**. Traditional methods often fail to address the uncertainties and vagueness in financial markets, which this method overcomes by introducing fuzzy logic and nature-inspired optimization.

---

### 🎯 Objective

- **Maximize** portfolio return  
- **Minimize** risk (variance)  
- Handle **uncertainty** using fuzzy logic  
- Find **optimal asset weights** using the Whale Optimization Algorithm

---

### 🤖 Fuzzy Set Logic

Fuzzy logic allows us to model uncertainty in real-world financial data. Instead of treating variables like "return" or "risk" as fixed numbers, we use **linguistic variables** such as:

- "High Return"
- "Low Risk"
- "Moderate Volatility"

These are represented by **membership functions**, turning crisp values into fuzzy sets. This enables smarter, more realistic decision-making in portfolio construction.

---

### 🐋 Whale Optimization Algorithm (WOA)

WOA is a **metaheuristic algorithm** inspired by the bubble-net hunting strategy of humpback whales. It works through:

- **Encircling prey**: Simulates the search for optimal solutions  
- **Bubble-net attacking**: Uses spiral movement and shrinking encircling to refine solutions  
- **Exploration phase**: Avoids local optima by exploring new areas in the solution space

This makes it effective for **non-linear, multi-objective financial problems**.

---

### ⚙️ Methodology

1. **Data Collection**  
   - Collect historical price data of selected stocks

2. **Fuzzy Logic Modeling**  
   - Define fuzzy sets for return and risk
   - Apply fuzzy inference rules to rate each asset

3. **WOA Implementation**  
   - Initialize whale population (portfolios)
   - Define fitness function (based on fuzzy scores and risk)
   - Update portfolios using WOA operations
   - Iterate until convergence

4. **Output**  
   - Optimal weights for selected stocks
   - Visualizations for return, risk, and convergence

---

### 📈 Tools & Technologies

- Python  
- `numpy`, `pandas`, `matplotlib`, `seaborn`  
- `scikit-fuzzy` for fuzzy logic  
- Custom WOA implementation in Python

---

### 🧩 Example Use Case

> Optimize a portfolio of NIFTY 50 stocks.  
> Use fuzzy rules to classify returns and risks.  
> Apply WOA to select the best combination of stocks that maximize fuzzy return while minimizing fuzzy risk.

---

### ✅ Key Features

- Realistic portfolio modeling using **fuzzy rules**  
- **Global optimization** using nature-inspired algorithm  
- Customizable constraints (e.g., budget, number of stocks)  
- Visual performance tracking


### 📷 Screenshots

![Dashboard Screenshot]((https://github.com/Navraj2004/portfoliooptimizationcode/blob/main/Screenshot%202025-05-26%20165905.png?raw=true)))
![Result Chart](assets/result_chart.png)

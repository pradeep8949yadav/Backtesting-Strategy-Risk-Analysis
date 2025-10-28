# Backtesting-&-Strategy-Risk-Analysis  
"Developed a robust quantitative backtesting and risk analysis framework implementing dynamic bet sizing, Combinatorial Purged Cross-Validation (CPCV), and Deflated Sharpe Ratio to ensure realistic strategy evaluation and mitigate overfitting risks."

---

## 📁 Project Information  
**Self Project — Quantitative Research | 2025**

---

## 🧠 Overview  
This project focuses on **realistic backtesting, performance evaluation, and risk assessment** of quantitative trading strategies using techniques from *López de Prado’s Advanced Financial Machine Learning (AFML)* (Chapters 10–15).  
The primary objective is to develop **robust evaluation pipelines** that avoid overfitting, incorporate **dynamic bet sizing**, and quantify risk-adjusted performance using statistically sound measures.

---

### 1. **Concepts Covered**

- **Bet Sizing:** Kelly criterion and probability-based sizing for dynamic capital allocation.  
- **Backtesting Errors:** Addressing overfitting, look-ahead bias, and data snooping in strategy testing.  
- **Combinatorial Purged Cross-Validation (CPCV):** Reliable model evaluation by removing overlapping data and testing multiple folds.  
- **Sharpe Ratio Adjustments:** Use of Deflated and Probabilistic Sharpe Ratios for robust performance validation.  
- **Strategy Risk Estimation:** Analysis of drawdowns, runs, and time-under-water metrics to evaluate capital resilience.  

---

### 2. **Tasks Performed**

1. **Dynamic Bet Sizing Implementation**  
   - Applied the **Kelly Criterion** and **probability-based bet sizing** to allocate position sizes dynamically based on predicted probabilities of trade success.  
   - Ensured that bet sizing adhered to risk constraints and drawdown limits.

2. **Combinatorial Purged Cross-Validation (CPCV)**  
   - Implemented CPCV to evaluate trading models while avoiding data leakage and overfitting.  
   - Used **combinatorial fold sampling** for robust out-of-sample performance measurement.

3. **Performance Metrics Calculation**  
   - Computed **Deflated Sharpe Ratio (DSR)** and **Probabilistic Sharpe Ratio (PSR)** to statistically validate profitability.  
   - Evaluated bias-corrected risk-adjusted returns under non-normal distributions.

4. **Strategy Risk Analysis**  
   - Calculated **drawdown depth**, **average run length**, and **time-under-water (TuW)** metrics for capital utilization efficiency.  
   - Analyzed **skewness and kurtosis** of return distributions to detect hidden tail risks.  

---

### 3. **Implementation Highlights**

- Designed a **modular backtesting framework** that supports dynamic bet sizing and CV-based evaluation.  
- Implemented **CPCV** for multi-fold testing to assess generalization across random partitions.  
- Combined **statistical robustness metrics** (DSR, PSR) with traditional backtest performance measures.  
- Developed visualization dashboards for **drawdown curves** and **underwater duration plots**.  

---

### 4. **Example Workflow**

1. **Predict Probabilities:** Use trained ML model to estimate event success probabilities.  
2. **Apply Bet Sizing:** Calculate position weights via Kelly or fractional Kelly sizing.  
3. **Run Backtest:** Use CPCV to simulate forward-looking results.  
4. **Compute Metrics:** Evaluate Sharpe, DSR, PSR, and drawdown statistics.  
5. **Risk Analysis:** Examine capital drawdowns and time-under-water periods for robustness.  

---

### 5. **Key Concepts**

- **Kelly Criterion:** Optimal bet fraction based on expected returns and win probability.  
- **CPCV:** Combines purging and embargoing to prevent information leakage while testing multiple random splits.  
- **Deflated Sharpe Ratio (DSR):** Adjusts Sharpe Ratio for multiple testing and overfitting bias.  
- **Probabilistic Sharpe Ratio (PSR):** Estimates the probability that a Sharpe Ratio is statistically significant.  
- **Drawdowns & Time-Under-Water:** Measures depth and duration of capital decline below previous peaks.  

---

### 6. **Tech Stack**

- **Language:** Python  
- **Libraries:** `numpy`, `pandas`, `scipy`, `matplotlib`, `statsmodels`, `mlfinlab`, `sklearn`  
- **Environment:** Jupyter Notebook / VS Code  

---

### 7. **Applications**

- **Strategy Evaluation:** Reliable performance testing for quantitative strategies.  
- **Risk Management:** Quantification of drawdown and underwater time for capital protection.  
- **Model Validation:** Use of CPCV and DSR to identify overfitting and confirm generalization.  
- **Portfolio Optimization:** Integrating probabilistic Sharpe ratios into multi-asset allocation.  

---

### 8. **Future Work**

- Integrate **online learning-based bet sizing** for adaptive portfolio allocation.  
- Extend framework to include **Bayesian Sharpe Ratio inference**.  
- Automate **CPCV pipeline** for multi-strategy backtesting at scale.  

---

 

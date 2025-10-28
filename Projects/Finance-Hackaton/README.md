# NGO Press Campaigns and Responsible Investment

This project investigates how **NGO press campaigns** affect the stock market performance of major **U.S. and European banks**.  
Using data from **SIGWATCH** (NGO campaign tracking) and **Datastream** (financial data), we estimate market reactions to positive and negative ESG-related events, applying an **event study** framework.

---

### Focus and Objectives
We focused on the following tasks:
1. **Estimate CAPM parameters** (and Fama-French 3 factors) for U.S. and EU banks.  
2. **Compute Cumulative Abnormal Returns (CARs)** around NGO campaign event dates.  
3. **Test the impact** of campaign sentiment, prominence, and timing (especially pre/post COP21).

---

### Methodology
- **Data Sources**:  
  - **SIGWATCH** — NGO campaign and sentiment data  
  - **Datastream** — stock returns for U.S. and EU banks  
  - **Fama-French 3 Factors** — Market risk - risk-free rate, SMB, HML  
- **Approach**:  
  - Rolling estimation of CAPM betas and alphas  
  - Computation of CARs over ±5, ±10, and ±15-day windows  
  - Statistical comparison of reactions by sentiment and period  

---

### Key Findings
- **Crisis Divergence (2009–2012)**: European banks became more value-oriented, while U.S. banks showed stronger market and size exposures.  
- **Eurozone Aftershock (2013–2016)**: Continued undervaluation and cyclical pressure in Europe; normalization in the U.S.  
- **Re-synchronization (2017–2020)**: Convergence in transatlantic bank risk sensitivities.  
- **Market Reaction**:  
  - Markets **reward neutrality** and **penalize extremes** (positive or negative sentiment).  
  - **Post-COP21**, both positive and negative campaigns triggered stronger negative reactions — CAR₁₀ ≈ −1.1% for negative events.  
  - Reaction amplitude is **higher in the U.S.**, indicating greater sentiment sensitivity and volatility.  

---

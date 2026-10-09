# WQU MSFE 690 CAPSTONE PROJECT – MODULE 4 DESIGN
**Project Proposal – Student Group 17830**
**Members:** Ting Ting Han, Henry Mayambu, Jonathan Matura
**Title:** Quantitative Assessment of ESG Materiality and Risk-Adjusted Performance of JSE-Listed Mining Equities (2014-2025)
**Repo:** esg-jse-mining-capstone | **Main:** `esg_jse_mining_analysis.ipynb`

### 1. Research Question
Do composite and pillar-level ESG (E,S,G) scores materially affect risk-adjusted returns, systematic beta, and conditional downside volatility for JSE mining equities after controlling for commodity/FX exposure and publication lags?
RQ1: Is β_E ≠ β_S ≠ β_G? RQ2: Does higher ESG reduce beta and EGARCH volatility?
H1: β_ESG ≠ 0, H2: β_E = β_S = β_G (Wald), H3: α_ESG tercile ≠ 0, H4a: θ_ESG <0, H4b: β_int <0

### 2. Motivation
Mining ~8% SA GDP and ~30% JSE cap, JSE Guidance June 2022. Western findings don't transfer due to load-shedding, MPRDA, B-BBEE. Gaps closed: (1) Pillar Black-Box, (2) Look-ahead bias, (3) KIO-AGL ownership.

### 3. Data – REAL + DISCLOSED SIMULATED
15 JSE miners Jan 2014-Jun 2025 (T=138): AGL.JO, IMP.JO, S32.JO, KIO.JO, SSW.JO, HAR.JO, GFI.JO, EXX.JO, ARI.JO, THA.JO, MRF.JO, PAN.JO, DRD.JO, NPH.JO, ASR.JO. Unbalanced: S32 122 obs, THA 135, NPH 46, ASR 77 (delisted). Raw 1,870 → 1,855 → 1,533 clean after 12m ESG lag. 165 annual ESG obs.
REAL via yfinance: GC=F, PL=F, HG=F, ZAR=X, ^IRX, JSE prices. Controls: CommodityExposure = Σ w_k * Δln(Price_k), FXRiskExposure = Δln(ZAR/USD) × CommodityExposure. ESG: try Refinitiv_ESG_scores.csv else print("No ESG file -> creating disclosed simulated") 45-85 trend. FYE lag: Dec effective July t+1, June Jan t+1, Sept Apr t+1. Assertion EffectiveDate <= Date.

### 4. Methodology
Model1 Two-Way FE: (Rit-Rft)=α+β1ESG+γ1Commodity+γ2FXRisk+μ_i+λ_t+ε, clustered SE.
Model2 Predictive Lag12: Eliminates reverse causality.
Model3 EGARCH-X: ln(σ²)=ω+α|ε|/σ+γ ε/σ+β ln(σ²_lag)+θ ESG. Varying θ (AGL -2.10, ARI -0.22 etc). γ<0 = leverage, θ<0 = dampening. DRD 505.33 outlier due illiquidity.
Beta interaction: (Rit-Rf)=α+β_m(Rm-Rf)+β_int(Rm-Rf)×ESG. Rm=ALSI/RESI10.
Portfolios: Annual July rebalance terciles, Jensen Alpha CAPM & SA FF3, Long/Short 10bps, CVaR95 -8.2% vs -12.5%. Charts: ESG Trends, Commodity Real, EGARCH Thetas varying.

### 5. Pain-Points
(1) Vol models ignoring ESG, (2) No tail/asymmetry, (3) Greenwashing/size confound. Solved via panel+EGARCH-X+CVaR+interaction+Wald.

### 6. Obstacles
Small N, illiquidity DRD/MRF, coal/gold/PGM heterogeneity, load-shedding 22-23, survivorship ASR, ESG methodology changes.

### 7. Real-Life Apps
Zambian Copperbelt KCM/Mopani/FQM ESG-linked loans, NAPSA ESG-tilt, insurance rehab liability, treasury hedging discount, JSE assurance evidence.

### 8. M3 Feedback Incorporation
Expanded 12 firms 2019-23 →15 firms 2014-25, Fixed constant Theta → varying Thetas, Added FYE 6m lag+ESG_lag12, Added Commodity/FX real controls, KIO robustness, clustered SE, Disclosure flag.

### 9. Expected Contribution
First JSE mining study with real commodity/FX+disclosed ESG, pillar Wald, EGARCH-X 12/13 negative gammas. Open-source reproducible.

### 10. Division
Ting Han: Lit review, FE, Wald. Henry: yfinance, EGARCH, CVaR, repo. Jonathan: Beta, alpha, README.

### 11. Repo & Prelim Results
Files: esg_jse_mining_analysis.ipynb, Commodity_FX_Data.csv (1,533 obs), EGARCH_Real_Thetas.csv, png/3 charts. Prelim: High-ESG vol 22.3% vs Low 31.7%, CVaR -8.2% vs -12.5%.

### 12. References MLA
Berg et al. Review of Finance 2022, Freeman 1984, Friedman NYT 1970, Giese et al. JPM 2019, JSE Guidance 2022, Kräussl et al. JIMF 2022, Matos CFA 2020, Refinitiv 2022.

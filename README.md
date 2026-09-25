# ESG Disclosure and Financial Performance: Evidence from JSE Mining Companies
**WQU | MSc Financial Engineering - Capstone | Owner: hmayambu-sys**

### Project Overview
Econometric analysis of ESG disclosures vs stock volatility/performance for JSE mining companies. Extends prior research (Mayambu, 2026). Research Context: Does ESG mitigate downside risk or is it greenwashing? Applies causal inference and panel methods.

### Research Questions
1. ESG scores vs stock returns?
2. Does ESG disclosure reduce volatility/downside risk (VaR/CVaR)?
3. Causal: risk-mitigation or disclosure-driven?

### Repository Structure
esg-jse-mining-capstone/
- README.md
- CONTRIBUTORS.md
- requirements.txt
- Project_Proposal_M4 Student Group 17830.pdf
- JSE_sample_data (1).csv (2019-2023 panel)
- ESG_vs_Returns.png
- esg_jse_mining_analysis.ipynb
- src/ (helper functions)

### Data
- Source: JSE listed mining firms, Annual Integrated Reports
- File: JSE_sample_data (1).csv - ESG scores, returns, volatility, market cap
- Period: 2019-2023

### Methodology
- Exploratory: Correlation ESG vs Returns (ESG_vs_Returns.png)
- Panel Models: Fixed Effects, Random Effects
- Risk Models: GARCH, CVaR
- Causal Inference: Causal Bayesian Networks (pgmpy) - Greenwashing vs Real Risk Mitigation
- Portfolio Test: ESG-screened vs unscreened
- Builds on: SSRN 7410578, SSRN 7181798

### Installation
git clone https://github.com/hmayambu-sys/esg-jse-mining-capstone.git
cd esg-jse-mining-capstone
pip install -r requirements.txt
jupyter notebook esg_jse_mining_analysis.ipynb

### Contributors
Henry Mayambu - Lead Researcher & Financial Engineer - @hmayambu-sys

### Citation
- Google Scholar: https://scholar.google.com/citations?user=sEA3LRkAAAAJ
- SSRN Author: 11727268
- ORCID: 0009-0007-8475-2558
- Cite: Mayambu, H. (2026). ESG Investing and Stock Market Returns: Evidence from South African Mining Equities. SSRN.

### License
MIT - Academic use (WQU Capstone) - Livingstone, Zambia | Sep 2026

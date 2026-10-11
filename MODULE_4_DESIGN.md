MScFE 690 Capstone Project: Module 4 Design
ESG Investing and Stock Market Returns: Evidence from South African Mining Equities
Project Proposal – Student Group 17830
Authors: Ting Ting Han, Henry Mayambu, Jonathan Matura

Abstract
This study quantitatively assesses the materiality and risk adjusted performance of mining stocks listed on the JSE from January 2014 to June 2025 with respect to their Environment, Social and Governance (ESG) materiality and risk levels. Mining accounts for around one third of the market capitalisation of the JSE, around 8% of South African GDP, but is under heavy sustainability scrutiny in the context of the Mining Charter III, King IV Code, the carbon tax and the JSE Sustainability and Climate Disclosure Guidance (June 2022). The study fills three gaps in the literature, (i) the published evidence is mainly from developed markets, which is not applicable in emerging markets where loadshedding, commodity price volatility and regulatory changes are key factors; (ii) the published evidence is based on composite ESG scores, which mask pillar-level trade-offs; and (iii) the published evidence is look-back, because annual ESG scores are not aligned with monthly returns. The study uses two-way fixed-effects panel regression, Instrumental Variable GMM (IV-GMM) for endogeneity, Disaggregated Pillar-level Wald tests for materiality, equal-weighted tercile portfolio sorts with CAPM and Fama-French three-factor alpha estimation, and asymmetric GARCH-X modelling for systematic risk and downside risk. The returns are aligned with the ESG scores, with a lag of six months for the scores to be published to avoid look-ahead bias, and the standard errors are clustered at the firm level, giving about 165 independent ESG observations. Finally, the study introduces, in a localized and open source manner, a framework of factors for the JSE mining sector which can be used by capital allocators as per Regulation 28 of the Pension Funds Act as a rigorous and a risk adjusted tool to support sustainable investment decisions.

Keywords: ESG investing, stock market returns, JSE mining equities, panel econometrics, GARCH volatility, sustainable finance, emerging markets, South Africa.

1. Introduction
1.1 Context and Purpose
The world of investment has gone from a checklist of ethics to an ethical duty of the investor. Mining is an integral part of South Africa's economy, accounting for about one-third of the South Africa Stock Exchange (JSE) market capitalisation, and contributing about 8% to South Africa's Gross Domestic Product (GDP) (Matos), but it also has a heavy burden of sustainability problems, including strict carbon and water regulations, strict labour laws, and socio-economic requirements, such as Broad Based Black Economic Empowerment (B-BBEE) and Mining Charter III compliance (Matos). As investors in the JSE have become more vocal about their desire for transparency with regards to ESG compliance, it is empirically still unclear whether the ESG performance generates or destroys value in this labour and carbon intensive industry.

This enquiry is framed by two perspectives of theory. Friedman's (1970) "Shareholder Primacy" model sees discretionary ESG spending as an agency cost which hurts short-term liquidity and stock prices (Edmans). The modern risk mitigation models of Freeman (1984) describe material ESG risk management as an investment in reputational capital that lowers the cost of capital in the longer term and safeguards against reputational harm and regulatory penalties. Good ESG practice could reduce the cost of capital and enhance returns in capital-intensive and politically-exposed sectors by reducing risk.

1.2 Research Problem
Although sustainable investing is becoming more and more popular, three gaps in the literature remain. First, the evidence available is mainly from developed Western markets, results from stable economies may not be applicable to economies in transition, emerging markets, or markets with a high degree of load shedding, volatile commodity prices and changing regulations (Kräussl et al.). Second, there is a South African mining paradox – investments in ESG (renewable energy as a solution to loadshedding, safety upgrades, community projects mandated under the Mineral and Petroleum Resources Development Act (MPRDA) and carbon tax are expensive – but can be a critical long-term hedge against fines and reputational damage. It is unclear what the reaction of the market will be, if any. Finally, the majority of studies lump ESG scores into a "black box". Recent research shows that returns are influenced differently by each pillar (Giese et al.): environmental and governance factors have an effect in the short-term, social factors have an effect in the long-term. Local level consensus on the concept of materiality for companies listed on the JSE in the mining sector is lacking (Berg et al.).

Fourth, a time lag exists because ESG scores are annual while returns are monthly. A majority of studies link annual ESG rankings to monthly returns and fail to take into account the look-ahead and publication lag of scores, with the result of exaggerated numbers of independent observations and look-ahead bias. This study fills this gap explicitly, with backward-aligning firm ESG scores with their publication dates and with aggregation of firm level standard errors.

A central research question is whether and to what extent ESG performance at the pillar level impacts the risk-adjusted returns of JSE-listed miners, without a local guide.

1.3 Research Questions
RQ1: Is there a difference in the impact of the individual E, S, and G pillars on stock returns?
RQ2: Can one conclude that ESG performance influences systematic risk and downside volatility of South African mining portfolios?

1.4 Hypothesis
Hypothesis Statement | Null | Alternative | Test
H1 Composite ESG affects monthly excess returns | β_ESG = 0 | β_ESG ≠ 0 | Two-way FE PanelOLS, clustered SEs
H2 Pillars have differential effects | β_E = β_S = β_G | At least one differs | Disaggregated panel + Wald test
H3 High-ESG portfolios earn positive risk-adjusted returns | α = 0 | α ≠ 0 | CAPM and FF3 alpha estimation
H4 ESG reduces systematic and downside volatility | θ_ESG = 0 | θ_ESG < 0 | Asymmetric GARCH-X variance equation

1.5 Significance
The study is useful for fine-tuning emerging market resource portfolios for asset managers, and for mining companies considering sustainability investments. It draws conclusions from 15 mining companies listed on the JSE, making it possible to generalise results for the sustainable finance literature in Africa, and to make inferences at the level of the pillars. The study adds to the literature because it explicitly addresses the issue of the frequency and timing of the publication of ESG scores (annual scores), which is not well reflected in the existing literature, as the monthly alignment of the annual ESG data is widely used but not necessarily sound. It also offers a localized and open source factor framework customized specifically for mining equities listed on the JSE, which it fills a gap in the market for institutional investors that are subject to Regulation 28 of the Pension Funds Act.

2. Theoretical Framework
2.1 Shareholder versus Stakeholder Theory
In the theory of corporate sustainability, there are conflicting views on the main goal of the company. Based on neoclassical economics, a company's primary obligation is maximising shareholders' profits. From this view, the economic cost of allocating funds to voluntary ESG initiatives is the increase in costs for compliance, administration and competitive disadvantage, which lowers short term liquidity and stock prices (Friedman; Pedersen et al.; Edmans).

The stakeholder theory, however, holds that creating value over the long-term is a matter of balancing the interests of multiple stakeholder groups – employees, the community, regulators, and environmental systems (Freeman). It also builds on that with modern risk-mitigation models arguing that having a strong ESG integration is a protective barrier against extreme financial risks, regulatory penalties and reputational damage (De Klerk and De Villiers). Better ESG practices reduce the cost of capital and enhance returns in capital intensive and politically sensitive industries via risk-reduction mechanisms.

2.2 Pillar-Specific Materiality
The ESG scores can be confusing because they are combined into an overall score. For mining equities, the dynamics that need to be considered under the E pillar are carbon transition risk exposure, regulatory compliance, and ecological damage liability (De Klerk and De Villiers). Environmentally intensive industries are typically characterized with negative environmental factor scores (environmental capital expenditure is high, future carbon taxes are uncertain, asset obsolescence is possible): stocks in such industries are more volatile, although effective environmental policies serve as a safeguard against the effect of future carbon taxes and asset obsolescence (Avramov et al.).

Social (S) and Governance (G) pillar dynamics are key to obtaining and maintaining a Social License to Operate (SLO) in emerging markets. Social issues may result from unsafe working conditions, unequal pay, and compelled labor that can trigger violence or closure of the site (Bauer & Hann, 2010). Governance mechanisms that limit information asymmetry, boost institutional investor confidence, and improve minority investor protections lead to higher valuations (Tobin's Q) for developing-economy companies. Khan et al. (2016) expanded this by identifying material and immaterial ESG factors, based on the SASB framework, and indicated that value creation is associated with material ESG factors, rather than with disclosures.

2.3 Empirical Evidence and Cross-Market Findings
The evidence on the empirical outcomes of the integration of ESG is mixed. Dimson et al. (2015) find a wide range of evidence, but it is clear that, in developed markets, active ESG engagement can significantly lower downside risk. For extractive industries, especially, financial impacts have been found to be contrary: Environmental liabilities raise credit risk and cost of debt financing, as pointed out by Bauer and Hann (2010). De Klerk and De Villiers and Johnson et al., indicated that the codes of good governance that were classified under King III/IV had positive relationship with improved disclosure, but disclosure was not always associated with market valuation premiums in South Africa. The final answer is therefore that as long as ESG practices lower risk, they do not directly help in return enhancement. One limitation is that composite scores are used for ESG instead of disclosing what is happening at the level of the pillars.

2.4 Methodological Development
Recent developments move away from simple linear regression models to dynamic, non-linear, and regime-specific models. Pedersen et al., proposed the ESG efficient frontier, which shows the impact of the ESG restrictions on the efficient frontier. Avramov et al., introduced uncertainty of ESG ratings into the equilibrium pricing model. Bolton and Kacperczyk introduced carbon beta and Just Transition risk, based on the notion of a persistent global carbon premium. After hitting these quantitative thresholds, this project discovers ESG alpha with the help of Refinitiv Asset 4 pillar scores and Fama French 5 factor and momentum models.

2.5 Mixed Empirical Evidence and Methodological Challenges
There are inconsistencies between studies in both countries and methods. Empirical divergence and rating disagreement suggest that longer time horizons might better detect a relationship between stock prices and sustainability ratings, although no statistically significant correlation is observed for shorter time periods, and conflicting results exist on whether positive or negative relationships exist (Avramov et al.; Blitson; Bolton and Kacperczyk). The differences are primarily due to the use of different methodologies for rating (Bloomberg, MSCI, Sustainalytics), sampling time periods, and specification errors in the models.

Prior studies have been criticised for their lack of attention to the econometric rigour, endogeneity and unobservables (firm-level heterogeneity and reverse causality). In recent years, panel data estimators like the Fixed Effects (FE) model, robust standard error clustering, and system Generalized Method of Moments (GMM) have become more popular to control for firm-specific factors and thus to obtain more precise causal effects (Wintoki et al.).

2.6 Where this Study Fits
Three-Part Empirical Gap:
- No Sector Focus: Cross sectional JSE studies do not consider dynamics in the extractive sectors.
- Aggregation Bias: Composite ESG scores ignore conflicting trade-offs between the E, S and G components.
- Uncaptured Regulatory Realities: Current studies do not take the developments up to 2025 into account, such as the Mining Charter III, the King IV and Carbon Border Adjustment Mechanisms (CBAM).

Dynamic panel estimators (two-way FE and IV-GMM) control for dynamic endogeneity, and augmented Fama-French 5 factor + momentum framework (Carhart 6 factor model) is integrated with a disaggregated Refinitiv Asset4 pillar model.

2.7 Competitor Analysis
Analysis Dimension | De Klerk et al. | Johnson et al. | Global Benchmark (Bauer and Hann; Bolton and Kacperczyk) | Our Study (Proposed)
Focus & Scope | CSR disclosure metrics, JSE Top 100 | Integrated reporting quality (King III/IV), wide SA stocks | Global/non-EM markets, environmental liabilities, carbon emissions | Performance-based ESG integration in JSE-listed mining stocks
Data & Timeline | Voluntary disclosure scores (pre-2018) | Post-2015 reporting quality | Global/US-centric datasets | Post-reform window (2014–2025): King IV, Mining Charter III, carbon transition
Primary Method | Cross-sectional correlations, simple OLS | Panel regressions of Tobin's Q on disclosure quality | Traditional asset pricing (Fama-French) or credit spread regressions | Augmented Fama-French multi-factor + dynamic panel estimators (FE/IV-GMM)
Key Limitations | No risk-adjustment controls | Mixes disclosure with real ESG performance | Ignores local socio-economic dynamics | Strict treatment of sector-specific data and dynamic endogeneity
Our Value Add | Baseline comparison | Pillar disaggregation | Localization & asset pricing | Investable insights: mining-specific risk-adjusted framework

2.8 Business Case
Commercial and practical viability of this model is being supported by South African asset managers and institutional investors in this country who are under tight regulatory constraints, specifically Regulation 28 of the Pension Funds Act. Although ESG factors are mandated to be incorporated into capital allocation decisions at the local level, there are no off-the-shelf global ESG factor models that can precisely value region-specific operational and regulatory risk in emerging markets. The project aims to meet a major market gap by delivering a factor framework that is open-source, localized and specific to JSE-listed mining stocks – a tool that institutional investors can use to meet compliance obligations and optimize portfolios while operating in a risk-adapted manner.

Strategic Market Positioning:
- Aggregate vs Disaggregation: This paper will examine each pillar individually, with its own set of environmental, social and governance risks/penalties.
- Methodological Superiority: Advanced panel econometric techniques (accounting for endogeneity and unobservables of firms) yield data relevant for the analysis of the JSE-listed mining industry that are reliable.
- Bridging Theory and Practice: Links ESG disclosures to financial returns via Tobin's Q approach and fluctuation in stock returns analysis, giving informative information for efficient asset allocation in risky developing economies.

3. Methodology
3.1 Research Design
This research is a Quantitative study with the model of panel econometrics and GARCH volatility. The research approach adopted is positivist approach which is based on observable and measurable data to test the hypotheses from financial economic theory. The design is a longitudinal design (2014-2025) and the secondary data used are data from Refinitiv ESG and Yahoo Finance.

3.2 Data and Sample
Sample: 15 JSE listed Mining Companies

Ticker | Company | FYE Month | Notes
AGL.JO | Anglo American plc | December | Majority owner of KIO
IMP.JO | Impala Platinum Holdings | June | 
S32.JO | South32 Limited | June | Listed May 2015 (121 obs)
SSW.JO | Sibanye-Stillwater | December | 
HAR.JO | Harmony Gold | June | 
GFI.JO | Gold Fields | December | 
EXX.JO | Exxaro Resources | December | 
ARI.JO | African Rainbow Minerals | June | 
THA.JO | Tharisa | September | Listed April 2014 (135 obs)
MRF.JO | Merafe Resources | December | 
PAN.JO | Pan African Resources | June | 
DRD.JO | DRDGold | June | 
NPH.JO | Northam Platinum | June | Listed September 2021 (46 obs)
ASR.JO | Assore | June | Delisted 2021 (88 obs)
KIO.JO | Kumba Iron Ore Limited | December | Majority owned by AGL

Period: January 2014 – June 2025 (monthly frequency)
Panel Structure: Unbalanced panel, ~1,850 firm-month observations

Ticker | Expected Observations
AGL.JO, IMP.JO, KIO.JO, SSW.JO, HAR.JO, GFI.JO, EXX.JO, ARI.JO, MRF.JO, PAN.JO, DRD.JO | 138 each
S32.JO | 121
THA.JO | 135
NPH.JO | 46
ASR.JO | 88
Total | 1,850

Dependent Variables:
- The amount of total returns (dividends included) in excess of the expected total return.
- The Sharpe ratio for the 12-month rolling period.

Independent Variables:
- Composite ESG score
- E, S, G pillar scores (individually)

Control Variables:
- The size of the firm (market capitalisation)
- Leverage
- Book-to-market ratio
- Commodity exposures (iron ore, copper, coal, manganese, aluminium, PGMs)
- ZAR/USD exchange rate

ESG Data Alignment and Timing:
Refinitiv ESG scores are fiscal year-end, and are calculated once per year. They are matched without look-ahead bias to monthly returns and are assigned to the months of the panels 6 months after the end of the fiscal year:
- December FYE firms (Anglo American, Kumba, Gold Fields, Exxaro, Merafe, Sibanye): FY2020 score starting in July 2020.
- June FYE firms (Impala, South32, Harmony, ARM, Pan African, DRDGold, Northam, Assore): FY2020 score from January 2021 onwards.
- September FYE firm (Tharisa): Score from March 2021 and onwards was used.
The standard errors are firm-specific and would be 165 (15 firms x 11 fiscal years) and not 1,850. Refinitiv notes that scores from the past five fiscal years are non-definitive and likely to be revised retroactively, which is a source of look-ahead bias in the subsample of scores from FY2020 to FY2025.

Corporate Actions Adjustment:
- The 2025 de-merger by Anglo American of its platinum business and consolidation of shares.
- The de-merger of South32 in 2015 from BHP Billiton.
- Price series restated to exclude price changes due to share consolidation and unbundling.

Kumba Iron Ore Independence:
Kumba Iron Ore (KIO.JO) - Anglo American plc (AGL.JO) is the majority owner. These two companies are observations made by the same group. This is known to be a limitation and robust analyses are provided in parallel to the main analyses.

3.3 Model specifications
Model 1: Two-Way Fixed Effects Panel Regression (H1: ESG – Return)
R_i,t = α0 + δR_i,t-1 + β1*ESG_i,t + γControls + μ_i + λ_t + ε_i,t
Where R_i,t = excess return for firm i at time t, ESG_i,t = composite ESG score, Controls = Size, Leverage, BTM, Commodity, ZARUSD, μ_i = entity (firm) fixed effects, λ_t = time fixed effects, ε_i,t = error term
Estimation: PanelOLS (EntityEffects and TimeEffects), clustered standard errors at firm level.
Validity: R² confirmed and the joint F-test confirmed.

Model 2: Instrumental Variable GMM (Endogeneity Corrections)
R_i,t = α0 + β1*ESG_i,t + γControls + ε_i,t
Instrument: Previous fiscal year's ESG (12-month lag, not monthly)
ESG_lag1_i,t = ESG_i,t-12
Estimation: IVGMM with robust standard errors.
Validity: AR(2) test p > 0.05; Hansen J-test p > 0.10.

Model 3: Asymmetric GARCH-X (H4: ESG-Volatility)
σ_i,t^2 = ω + α*ε_t-1^2 + β*σ_t-1^2 + θ*ESG_i,t
Where: σ_i,t^2 = conditional variance, θ = ESG coefficient in variance equation, If θ<0 and significant, ESG lowers volatility
Estimation: arch_model with mean="AR", vol="GARCH", p=1, q=1, x=ESG.
Validity: AIC/BIC and significance test for θ<0.

Model 4: Portfolio Sorts and Factor Alphas (H3: Risk-Adjusted Performance)
Tercile Portfolio Construction:
- Classify companies according to their composite ESG scores, monthly.
- Form equal-weighted tercile portfolios (High, Medium, Low ESG)
- Rebalance monthly
- Use the G12+60 stock portfolio to build a long-short portfolio (High ESG – Low ESG).

Alpha Estimation
CAPM: R_p,t - R_f,t = α_p + β_p(R_m,t - R_f,t) + ε_p,t
Fama-French Three-Factor: R_p,t - R_f,t = α_p + β_p(R_m,t - R_f,t) + s_p*SMB_t + h_p*HML_t + ε_p,t
Validity: Alpha significance (t-test), Sharpe ratio, maximum drawdown.

4.4 Data Analysis Procedure
Step | Procedure | Software | Output
1 | Data acquisition (Yahoo Finance prices, Refinitiv ESG) | Python 3.11 | Raw datasets
2 | ESG alignment with 6-month publication lag | pandas merge_asof | Aligned panel
3 | Excess return and Sharpe ratio calculation | Pandas | Dependent variables
4 | Descriptive statistics and scatter plots | matplotlib | Illustrative figures
5 | Model 1: Two-way FE panel regression | linearmodels.PanelOLS | β_ESG, R², F-test
6 | Model 2: IV-GMM with lagged ESG instrument | linearmodels.IVGMM | β_ESG, AR(2), Hansen J
7 | Model 3: Asymmetric GARCH-X per firm | Arch | θ_ESG, AIC/BIC
8 | Model 4: Tercile portfolio sorts and alpha estimation | pandas, statsmodels | α, Sharpe, max drawdown
9 | Pillar-level Wald test (H2) | linearmodels | Wald statistic, p-value
10 | Visualization and reporting | matplotlib, seaborn | Figures and tables

4.5 Constraints and Mitigation
Constraint | Impact | Mitigation
Unbalanced panel (firm entries/exits) | Reduced power in some periods | Report per-firm observation counts; robustness checks
KIO/AGL non-independence | Violates independence assumption | Robustness checks without Kumba
Annual ESG vs monthly returns | Look-ahead bias, inflated N | 6-month publication lag; firm-clustered SEs; report 165 independent ESG obs
Refinitiv retroactive revisions (FY2020–FY2025) | Look-ahead bias in recent subsample | Sensitivity analysis; flag as limitation
Small number of independent ESG observations (165) | Limited power for pillar tests | Wald test with adjusted degrees of freedom
Corporate actions (de-mergers, consolidations) | Price discontinuities | Restate price series; adjust for unbundling
Commodity super-cycle 2021–2022 | Confounding volatility | Commodity-specific controls; time fixed effects
Loadshedding events | Idiosyncratic volatility | Time fixed effects; robustness with event dummies

4.6 Source Code Development
To help facilitate teamwork, version control and sharing between the team and instructor, the project code is hosted in a private Git repository on GitHub, following the guidelines outlined in the MScFE 690 Source Code Development guidelines. At the highest level, it includes a README.md file that provides a description of the project, how to set up, and how it is executed; a requirements.txt file that lists down all the python packages needed so that the instructor can install everything once with the command pip install -r requirements.txt; a CONTRIBUTORS.md file that documents the roles of contributors and their responsibilities; a config.yaml file that specifies the ticker symbol, date ranges, fiscal year-end months, and model settings in a centralised manner; and a .gitignore file that excludes data files, outputs and credentials from version control.

The data is stored in two folders: data/raw includes the original Refinitiv ESG scores and JSE price data and data/processed includes the cleaned and aligned panel data for the analysis. All core Python code is in the src folder, broken into small modules: data_loader.py is for loading and acquiring the data, esg_alignment.py is for aligning by the six-month publication lag using merge_asof, returns.py is for the calculation of excess returns and Sharpe ratios, panel_models.py is for the two-way fixed effects model and IV-GMM estimation, garch_models.py is for the asymmetric GARCH-X estimation, portfolio_sorts.py is for the construction of tercile portfolios and estimation of alphas, and visualization.py is for the creation of figures and tables.

The notebooks folder includes four jupyter notebooks for a step-by-step guide to the analysis: data exploration, panel regression, GARCH analysis, and portfolio backtest. Results are stored in the outputs folder, the figures (as 300 dpi PNGs) in one subfolder, and the regression and summary tables in another. The last one is the tests folder which includes unit tests for the alignment part: test_alignment.py, and the models part: test_models.py, to ensure the reproducibility and correctness of the results.

The following structure follows the Source Code Development Guidelines: a private Git repository, full access for team members, read-only access for instructor, a requirements.txt file for installation of all dependencies, documentation (README, config, contributors). Full access link that can be shared with the instructor for review via HTTPS.

5. Results (Planned Structure)
5.1 Descriptive Statistics
- Table 2: Hazardous materials holdings (as defined by the National Oil Corporation)
- Table 3: Correlation matrix
- Figure 2: Trend of ESG scores over time for firms
- Figure 2: Distribution of returns by ESG quartile

5.2 Panel Regression Results (H1)
- Table 3: Two-way FE panel regression results for Model 1.
- Table 4: IV-GMM results for the lagged ESG instrument (Model 2).
- Table 5: Robustness checks - no Kumba

5.3 Pillar-Level Materiality (H2)
- Table 6: Panel regression results – disaggregated by pillars (E, S, G)
- Table 7: Wald test for joint equality (β_E = β_S = β_G)
- Figure 3: Scatter plots of E, S, G vs Sharpe ratio

5.4 Portfolio Sort Results (H3)
- Table 8: Tercile portfolio characteristics
- Table 9: Alphas of CAPM and FF3 by tercile
- Table 10: Sharpe (Max Drawdown) of a long-short portfolio
- Figure 4: Cumulative returns of High vs Low ESG portfolios

5.5 GARCH-X Results (H4)
- Table 11: GARCH-X parameter estimates by firm
- Table 12: Significance summary for ESG's θ.
- Figure 5: Conditional volatility paths according to the quartiles of the ESG ratings.

5.6 Validity Diagnostics
- Table 13: AR(2) and Hansen J-test results
- Table 14: AIC and BIC values for GARCH models.
- Table 15: Number of independent ESG observations (≈165) compared with number of raw panel observations (≈1,850).

6. Discussion (Planned Structure)
6.1 Interpretation of Results
- The appropriateness of composite ESG (H2)
- Which pillars are material (H2)
- Whether high-ESG portfolios are able to generate positive alpha (H3)
- Does ESG reduce volatility (H4)?

6.2 Relation to Existing Literature
- Friede et al. (2015) meta-analysis was used to compare the findings.
- Compare with De Klerk & De Villiers (2012) and Johnson et al. (2020) on JSE
- The materiality framework of Khan et al. (2016) was extended to South African mining.
- The carbon premium is consistent with Bolton & Kacperczyk (2021).

6.3 Theoretical Implications
- Explain the pro and the con arguments for and against stakeholder theory and shareholder primacy.
- Studies on the risk-reduction channel vs the return-enhancement channel
- The materiality of emerging market mining.

6.4 Practical Implications
- Further Regulation 28 guidance for asset managers.
- Consequences for the sustainability investment of mining companies.
- The JSE will implement additional ESG assurance requirements.

6.5 Limitations
- The ESG observations are not balanced by the panel, and only small independent observations exist.
- KIO/AGL non-independence
- Refinitiv retroactive revisions
- Survivors bias (delisted companies)
- Commodity super-cycle confounding
- The limitations of mitigating for look-ahead bias

7. Conclusion (Planned Structure)
- Summary of the results for each of the hypotheses.
- Africa Sustainable Finance Literature: Contribution
- Select methodological contribution (Look-ahead Bias Correction, Pillar-level Materiality)
- Practical contribution (open-source framework for JSE mining)
- No new ideas or data introduced

**References**

- Avramov, Doron, et al. "Sustainable investing with ESG rating uncertainty." *Journal of Financial Economics*, vol. 145,      no. 2, 2022, pp. 642-664.
- Bauer, Rob, and Daniel Hann. "Corporate Environmental Management and Credit Risk." SSRN, 2010.
- Berg, Florian, et al. "Aggregate Confusion: The Divergence of ESG Ratings." *Review of Finance*, vol. 26, no. 6, 2022, pp.   1315-1344.
- Biltson, Kristian. "ESG Rating Disagreement and the Effects on Stock Returns." 2023.
- Bollerslev, Tim. "Generalized Autoregressive Conditional Heteroskedasticity." *Journal of Econometrics*, vol. 31, 1986,      pp. 307-327.
- Bolton, Patrick, and Marcin Kacperczyk. "Do Investors Care about Carbon Risk?" *Journal of Financial Economics*, vol. 142,   no. 2, 2021, pp. 517-549.
- De Klerk, M., and C. De Villiers. "The Value Relevance of Corporate Responsibility Reporting." *Meditari Accountancy         Research*, vol. 20, no. 2, 2012, pp. 95-115.
- Dimson, Elroy, et al. "Active Ownership." *Review of Financial Studies*, vol. 28, no. 12, 2015, pp. 3225-3268.
- Edmans, Alex. "Does the Stock Market Fully Value Intangibles? Employee Satisfaction and Equity Prices." *Journal of          Financial Economics*, vol. 101, no. 3, 2011, pp. 621-640.
- Freeman, R. Edward. *Strategic Management: A Stakeholder Approach*. Pitman, 1984.
- Friede, Gunnar, Timo Busch, and Alexander Bassen. "ESG and financial performance: Aggregated evidence from more than 2000    empirical studies." *Journal of Sustainable Finance & Investment*, vol. 5, no. 4, 2015, pp. 210-233.
- Friedman, Milton. "The Social Responsibility of Business Is to Increase Its Profits." *The New York Times Magazine*, 13      Sept. 1970.
- Giese, Guido, et al. "Foundations of ESG Investing: How ESG Affects Equity Valuation, Risk, and Performance." *Journal of    Portfolio Management*, vol. 45, no. 5, 2019, pp. 69-83.
- Johannesburg Stock Exchange. *JSE Sustainability and Climate Disclosure Guidance*. JSE, June 2022.
- Johnson, R., et al. "The Impact of King IV on Integrated Reporting in South Africa." *South African Journal of Accounting    Research*, 2020.
- Khan, Mozaffar, et al. "Corporate Sustainability: First Evidence on Materiality." *The Accounting Review*, vol. 91, no. 6,   2016, pp. 1697-1724.

Market Risk
1. VaR
2. Backtesitng VaR
3. Correlation Risk

OP risk
1. ERM framewrok: enterprise risk mgmt
2. RORAC and AROROC: return on risk-adjusted capital
3. Economic Captial
4. Model risk
5. Stress testing
6. Outsourcing risk

Basel Accord
Capital required > Asset*x%

Liquidity Risk
1. Funding liq risk / market liq risk
2. Endo / exco liq risk
3. Intra-day liq risk
4. Leverage risk
5. Illiq assest mgt

6 Risk mgt
1. Factor theory
2. Portfolio construction
3. Risk budgeting
4. Performance attribution
5. Hedge fund/ mutual fund

7 Current Issues
1. blockchain
2. AI 
3. climate change
4. reference rate: risk free rate


R = lnP1 - lnP0


VaR
loss day
loss value
loss possibility

u +/- 1.65o

- Profit/Loss
  - P/L: substraction
  - Arithmetic Return: r: ratio
  - Geometric Return: Rt: log ratio, = ln(1 + r)
    - diff is negligible in short term, may substantial long term
- VaR
  - normal VaR
    - arithmetic return is normal
    - geometric return is normal: 1- e^avar
  - Cohension risk measure
    - weighed VaR
    - eventually converge as num of slice larger
  - Conditional VaR: expected shortfall, E on value left of VaR
- Quantile-Quantile Plots
  - test if data fit a distribution -> linear

## Risk Management and Portfolio management
### Factor Theory
- risk factor
  - diff under diff circumstance
  - not asset
  - will be compensated by risk premiums
  - CAPM: beta
  - SDF: stochastic discount factors
  - Multifactor model: like APT(arbitrage pricing theory)
- Gold: assets paying off in bad times have **low** risk premiums(>0), in some circumtance, they are also defined as valuable assets 
- Efficient Market Theory: weak, semi-strong, and strong efficiency; nearly efficiency
- There are seven major shortcomings of CAPM
  - Investors only have financial wealth.(human wealth)
  - Investors have mean-variance utility.
  - Investors have single period investment horizon. 
  - Investors have homogeneous (identical) expectations.
  - Market are frictionless. 
  - All investors are price takers. (can't affect market)
  - Information is free and available to everyone.
 
- factor types
  - marco, fundamental-based
    - economic growth: -
    - Inflation: -
    - volatility: - realized return
      - vol protection: volatility swap, out-of-money puts
    - productivity(GDP)
    - demographic(labor)
    - prolitical(sovereign)
  - investement style
    - static
    - dynamic
      - value and size
        - divident, EPS
        - HML: book value
        - SMB: cap
      - Momentum: WML
        - Matthew effect

- Alpha
  - Benchmark
    - well defined
    - tradable
    - replicable
    - adjusted for risk
      - factor regression: risk-adjusted factor benchmark 
  - Rt = alpha + (1 - beta)Rf + betaRb + err
       = alpha + Rf + beta(Rb - Rf) + err
       = Jensen's alpha + CAPM(new Benchmark)
  - style analysis
    - style weight
- low risk anomaly
  - risk anomaly explaination
    - data mining
    - leverage constraints
    - agency problem: can't short
    - preference

### Portfolio construction
- portfolio construction inputs
  - transaction cost
  - alpha
    - refining alpha
      - scale the alpha: = vol x IC(info coefficient) x Score
    - trim alpha outliners: +/- 2.5%
    - neutralization: benchmark
  - current portfolio
  - covarience
  - active risk aversion: customer type; lambda = IR / (2 TEV)
  









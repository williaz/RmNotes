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
TEV, Marginal contributio

- 5 portfolio construction inputs
  - transaction cost
  - alpha
    - refining alpha
      - scale the alpha: = vol x IC(info coefficient) x Score
    - trim alpha outliners: +/- 2.5%
    - neutralization: benchmark
  - current portfolio
  - covarience
  - active risk aversion: customer type; lambda = IR / (2 TEV)
  
- 4 portfolio construction techniques
  - Screens: rank top alpha
  - Stratification: layered screaning
  - Linear programming
    - dimensions of riks, industry, size, vol and beta
  - Quadratic programming
    - more inputs
    - Explicitly considers all three elements: alpha, risk, and transactions costs.
- Portfolio Revisions and Rebalancing
  - trade-off between expected active return, active risk and transaction costs
  - MCVA𝑛 = alpha − 2 × 𝜆𝐴 × 𝜑 × MCAR𝑛 : Marginal contribution to value added for stock n
  - non-trade region```2 × 𝜆𝐴 × 𝜑 × MCAR𝑛 − SC𝑛 ≤ a𝑛 ≤ 2 × 𝜆𝐴 × 𝜑 × MCAR𝑛 + PC𝑛```
    - MCAR𝑛 : Marginal contribution to active risk of asset n.
    - 𝜆𝐴: risk aversion of investor
    - 𝜑: active risk
    - selling/purchase cost
  - Dispersion

### Portfolio Risk Measure

- Marginal VaR
  - MVaRa = 𝜕VaRp/𝜕Va = Z𝛼 × Cov(Ra, Rp)/𝜎p = Z𝛼 × 𝜌a,p × 𝜎a = Z𝛼 × 𝛽a,p × 𝜎𝑃 = 𝑉aRp/Vp × 𝜌a,p
- Incremental VaR: VaR(p+a) - VaRp = MVaRa x Wa
- Component VaR: CVaRa = MVaRa x Va

- 3 legged risk management stool
  - risk plan
  - risk budgeting: asset allocation
    - across asset classes
    - across active manager
  - risk monitoring
    - VaR

- VaR to diff risks
  - Absolute Risk VS Relative Risk(to Benchmark)
    - TE = Rp -Rb
    - TEV(tracking err vol)
  - Policy mix risk VS active mgt risk
  - Funding risk: 
    - Surplus = asset - liablity
    - σSurplus
  - Sponsor risk: owner


### Performance Measure and Evaluatiion

- Measure
  - Green zone
    - G: usual event, insignificant dev
    - Y: unusual but expected
    - R: truely unusual, immediate follow-up
  - Sharp and information ratio
    - return calc
      - holding period return
      - time wighted
      - dollar weighted: IRR(Internal rate of return)
  - Alpha vs Benchmark
  - Alpha vs Peer group
  - Attribution of return

- Risk adjusted return
  - Total risk adjusted return: Modigliani-Squared
    - M^2 measure of performance 
      - sharp: (Rp - Rfree) / 𝜎p
      - 𝜎𝑀× (SR𝑃 − SR𝑀) 
  - Systematic risk adjusted return: Treynor Ratio
    - T^2 measure of performance
  - Unsystematic risk adjusted return
    - IR measure of performance = excess return / TEV
    - V-vol
- Info ratio: IR ~= IC x BR^.5 (BR: breadth of strat)

- Excess return = E(Rp) - E(Rb) = TE
- t-value for alpha = alpha / std err of alpha = N^2 x IR
  - IR = alpha / 𝜎alpha

- Market timing ability
  - call option model
  - performance attribution
    - sector selection
    - security selection 

### Hedge fund
- Bias in
  - Survivorship Bias
  - Self-Selection Bias: same manager, poor performing ones of funds
  - Backfill Bias

- Evolution
  - 98 LTCM
  - 2000 .com
  
- Strategies
  - Directional: Trend follower and Global Marco
    - Managed futures: only future
    - Global macro; long call and short put
  - Event-driven: Risk arbitrage & distressed
    - Risk(Merger) arbitrage
      - deal risk
    - Distressed securities(fallen angle)
      - financial distress => jonk bond
      - mispricing
      
  - Relative value and arbitrage like strategies
    - Fixed income arbi
      - duration = 0
      - financial instrument: negative skewness
    - convertible bond
      - delta = 0
      - long gamma & vega
    - long/short equity
      - beta ~= 0
  - Niche
    - Dedicated short bias
    - Emerging market
    - Equity market neutral
- FoF (fund of hedge fund)
  - fees


- Hedge fund risks
  - Liquidity risk
    - iliiquid assets
      - low correlation
      - low vol
      - high serial correlation
  - Leverage Risk
    - crowded trade risk
  - Agency Risk
    - incentive fee
    - cost of fund closure
    - GP(manager) own money
    - water marks / clawback
  - Style Drift Risk
    - size
    - leverage
  - Fraud risk
    - Unscrupulous hedge fm
    - Ponzi schema
    - Due diligence
      - process
        - Investment process:  What is your strategy, and how does it work?  How is equity ownership allocated among the portfolio management, trading, and research Teams?  Is the track record reliable?  Who are the principals, and are they trustworthy?
        - Related risk controls:  How is risk measured and managed?  How are securities valued?  What is the portfolio leverage and liquidity?  Does the strategy expose the investor to tail risk?  How often do investors get risk reports, and what do they include?  Do the fund terms make sense for the strategy?
        - Operational Environment:  Internal Control Assessment  Documents and Disclosures  Service Provider Evaluation
        - Model Risk and Fraud Risk








De'Longhi DCF valuation at FY2025
=================================

A five-year free-cash-flow (FCFF) discounted cash flow valuation of De'Longhi S.p.A. (Borsa Italiana: DLG), with scenarios, a sensitivity grid, a Monte Carlo simulation and a peer-multiple cross-check. The valuation date is 31 December 2025.
This project employed AI for planning, generating and verifying each step. Full disclosure in README_AI_USAGE.txt


KEY RESULT
----------
Base-case value per share (Gordon growth terminal value):   EUR 80.0
Market price at 31 December 2025:                           EUR 36.5
The base DCF value is 119.2% above the market price.

This gap is mostly a statement about the discount rate, not about the market being wrong:
the peer-multiple value is EUR 39.0, close to the market price. The result is fragile (see
Limitations).


METHODOLOGY
-----------
- FCFF = EBIT x (1 - tax) + D&A - capex - increase in working capital; leases (IFRS 16) are treated as debt, so lease payments are not deducted from FCFF.
- Forecast horizon: five years, FY2026 to FY2030, from five years of cleaned history.
- WACC: CAPM with the 10-year Italian government bond yield, the mature-market equity risk premium and Damodaran's European industry beta, re-levered at De'Longhi's capital structure.
- Terminal value: Gordon growth, cross-checked with an EV/EBITDA exit multiple from six peers.
- Stress tests: bull and bear cases, a WACC by terminal-growth grid, and 10,000 Monte Carlo runs.


KEY ASSUMPTIONS
---------------
Assumption                      Value
------------------------------  ----------------------------------------------------
WACC                            5.11%
  Risk-free rate                3.552%
  Equity risk premium           4.23%
  Re-levered beta               0.425
Terminal growth                 2.0%
Revenue growth                  5.0% in FY2026, easing to 2.0% by FY2030 (average 3.5%)
Adjusted EBIT margin            12.88% in FY2026 to 12.22% in FY2030 (average 12.55%)
Tax rate                        23.7% (historical average)
Capex                           EUR 150 m in FY2026, easing to 3.15% of revenue
Net debt incl. leases           EUR -707.267 m (net cash)
Net shares                      149.523224 million
Exit multiple (peers)           9.0 x EBITDA (weighted)


LIMITATIONS AND DISCLAIMER
--------------------------
- This is a personal project of a BSc undergraduate in statistics and economics. It is not investment advice and not a buy or sell recommendation.
- The terminal value is 86.4% of enterprise value, and WACC is only 3.11 points above terminal growth, so small changes in either move the value A LOT. Across the sensitivity grid the value runs from EUR 51.6 to EUR 210.5 per share.
- The low WACC comes mainly from a low industry beta. Peers trade at about 9 times EBITDA, while the base DCF implies about 19 times.
- The risk-free rate is the December 2025 average of the Italian 10-year yield (a proxy for 31 December 2025). No management targets exist after 2026. Some peers have period or lease mismatches, listed in the report.
- Data cutoff: the share price and the market data are as at 31 December 2025. The latest source documents were published in February 2026. Free public sources only.


ABOUT ME
Mina Khella. BSc Statistics & Economics, Università degli studi di Milano-Bicocca. 
Linkedin -> https://www.linkedin.com/in/mina-khella-812113182/
e-mail   -> mina.khellas@gmail.com

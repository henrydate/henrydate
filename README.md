# Henry Date

**Valuation, financial modelling, and the data tooling behind rigorous analysis.**

Melbourne-based finance professional and Chartered Accountants Program candidate (CA ANZ, completing early 2027), with three years of financial analysis at a boutique advisory firm, a buy-side research internship, and a decade as an active equity investor. I build company financial and valuation models from first principles, think bottom-up about business quality, and write the Python and data tooling that supports a rigorous analytical process. My work centres on understanding what a business is worth, and why.

## Focus

* **Fundamental research:** bottom-up company analysis, business-quality and competitive-moat assessment, investment-thesis construction
* **Valuation & modelling:** three-statement models, DCF with full WACC build, trading comparables, precedent transactions, scenario and sensitivity analysis
* **Data & tooling:** Python (Pandas, NumPy), web scraping (Playwright, BeautifulSoup), official-data ingestion (ABS SDMX, RBA, CKAN, RTA), resilient connector design, and applied econometrics (panel regressions, difference-in-differences)

## Featured Projects

* **Australian housing-data series:** three state pipelines (**NSW · VIC · QLD**) on a shared SQLite engine, each adapted to that state's free-data landscape, with resilient official-data connectors, demand-side drivers (ABS migration/population), and an analysis layer.
  * **[nsw-housing-data](https://github.com/henrydate/nsw-housing-data):** NSW Valuer-General **transaction-level** sales (every sale, with price, land area and suburb), enabling true suburb medians, full price distributions and price-per-m² of land
  * **[vic-housing-data](https://github.com/henrydate/vic-housing-data):** Valuer-General suburb medians + DFFH rents, with rental-yield decomposition, cash-rate sensitivity and an interstate **difference-in-differences** on Victorian housing policy
  * **[qld-housing-data](https://github.com/henrydate/qld-housing-data):** RTA bond-lodgement rents at suburb/postcode granularity + an interactive postcode rent explorer (Excel); Brisbane-boom / rent-crisis analysis
* **asx-coverage-toolkit:** a screening and coverage-universe toolkit over the listed Australian market (sector, index membership, key metrics, consensus), built as a self-serve research-triage tool
* **[commodities-intelligence](https://github.com/henrydate/commodities-intelligence):** a cross-asset forecasting and correlation system spanning oil, gas, FX and equity markets alongside 30+ macro drivers, built for corporate hedging and portfolio management.
  * **Interactive Streamlit dashboard** with eight analytical views, including correlation and R² matrices, macro-driver ranking, multi-factor regression models, rolling correlation, a price explorer, and 90-day LSTM forecasts
  * **Full historical data** back to 1997, sourced live from FRED, Yahoo Finance and the RBA, with frequency-aware analysis (daily returns for prices, annual-horizon changes for macro series)
  * **Australia deep-dive** on what moves the ASX 200 and the Australian dollar, including the finding that the RBA cash rate has no independent effect on the index once global risk and the commodity cycle are accounted for
* **equity-valuation-models:** a documented three-statement + DCF + comparables modelling framework, with a worked illustrative example and methodology notes
* **Optimising_TA / awhaleofaportfolio:** earlier quantitative and FinTech projects (ensemble-ML signal testing; risk-weighted portfolio construction)

## Toolbox

Excel (advanced) · Python (Pandas, NumPy) · SQL · Data Pipelines · DCF & Valuation Modelling · Financial Statement Analysis · PowerPoint

## Background

B.Com (Accounting) & B.Finance, Monash University · Monash/edX FinTech Boot Camp · CA Program (CA ANZ, in progress) · Accountant, Harlen Advisory · Former Equity Research Intern, Vachi Capital

## Contact

* **[LinkedIn](https://www.linkedin.com/in/henry-date/)**
  
---

*Everything here is personal project work, shared to demonstrate analytical and technical capability. It is general information and educational material only, not financial product advice or a recommendation, and I am not licensed to provide financial advice. See individual repository disclaimers.*

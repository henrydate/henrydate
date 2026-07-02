# Henry Date

**Valuation and financial modelling, with the data tooling and audit trail behind defensible analysis.**

Melbourne-based finance professional and Chartered Accountants Australia and New Zealand (CA ANZ) candidate, on track to complete the program in early 2027. Three years across tax advisory, financial analysis, and compliance in a boutique firm, a buy-side research internship, and over a decade as an equity investor. I build company financial and valuation models from first principles, take a bottom-up approach to assessing business quality, and write Python tooling to source, verify, and analyse the data underneath. The throughline across everything here is the same: every assumption sourced, every figure dated, every discretionary call logged, because a valuation is only as defensible as the evidence behind it.

## Featured work

### [equity-valuation-models](https://github.com/henrydate/equity-valuation-models)
**Single-name valuation framework with an auditable assumption ledger. Ships with a full primary-source BHP valuation.**

A single-name equity valuation framework built around one idea: a valuation is only as defensible as its assumptions, so every assumption is sourced, challenged, and logged to an auditable assumption-and-evidence ledger. Ships with a real, primary-source BHP valuation (FY25 filings plus live market data), not just a demo: WACC build, sum-of-parts, and a normalised DCF cross-check that triangulate to a blended fair value, with every input dated and cited to the page. Includes a deterministic elicitation wizard that demands a source, rationale, and confidence for each discretionary input, reasonableness guardrails that surface as logged overrides, an articulated three-statement model with a foot-and-tie integrity validator, an EV/EBITDA and DCF comparables engine, and a research-note and Excel-workbook generator. 62 passing tests.

*Sample output, no install needed: [BHP research note](https://github.com/henrydate/equity-valuation-models/blob/main/output/BHP_real_note.md) · [Excel model](https://github.com/henrydate/equity-valuation-models/blob/main/output/BHP_real_model.xlsx) · [walkthrough notebook](https://github.com/henrydate/equity-valuation-models/blob/main/showcase.ipynb)*

### [asx_coverage_toolkit](https://github.com/henrydate/asx_coverage_toolkit)
**The entire ASX, around 1,979 entities, packaged into a colour-coded, filterable Excel research database regenerated on demand from live data.**

A screening and coverage-universe tool over the entire ASX-listed market, regenerated on demand from live Yahoo Finance data, layered with four-tier GICS classification, S&P/ASX index membership, and a personal Buy/Hold/Sell and analysis-progress tracker, rendered to a colour-coded, filterable Excel research database. Every row is labelled with its data source and confidence tier.

*Sample output: [workbook screenshots](https://github.com/henrydate/asx_coverage_toolkit#workbook-preview) · [the Excel database itself](https://github.com/henrydate/asx_coverage_toolkit/blob/main/output/ASX_Master_Database.xlsx)*

### [commodities-intelligence](https://github.com/henrydate/commodities-intelligence)
**What moves oil, gas, the Australian dollar and equity markets, quantified over 30 years of history with the statistics to back every claim.**

A cross-asset forecasting and correlation system spanning oil, gas, FX, and equity markets against 30-plus macro drivers: correlation and R-squared matrices, single- and multi-factor regression with standardised betas, VIF multicollinearity checks and incremental-R-squared build-up, rolling correlation, and a 90-day LSTM benchmarked against naive baselines. Full history back to 1997, sourced live from FRED, Yahoo Finance, and the RBA, with frequency-aware transforms (returns for prices, year-on-year for nominal levels, first differences for rates). Interactive Streamlit dashboard across eight analytical views. Headline Australia finding: the RBA cash rate has no independent effect on the ASX 200 once global risk and the commodity cycle are accounted for.

### [portfolio-reporting-pipeline](https://github.com/henrydate/portfolio-reporting-pipeline)
**SQL-backed performance and risk reporting for price histories too large to open by hand.**

A data-infrastructure tool built around one constraint: the data is too large to open by hand, so the work is search, filter, and query through scripts, not eyeballing a file. Chunked CSV ingestion at flat memory (1.3M rows in around 20 seconds), indexed SQL queries returning slices in milliseconds, and standard performance and risk analytics (returns, volatility, Sharpe, drawdown, tracking error, contribution) with hand-checked unit tests.

### Australian housing-data series
**Three reproducible state pipelines (NSW, VIC, QLD) on a shared SQLite engine, each adapted to that state's free-data landscape.**

Built end to end from resilient official-data connectors through to an econometric analysis layer.
- **[nsw-housing-data](https://github.com/henrydate/nsw-housing-data)**: NSW Valuer-General transaction-level sales (every individual sale, with price, land area, and suburb), enabling true suburb medians, full price distributions, and price per square metre of land. The data the other states do not release for free.
- **[vic-housing-data](https://github.com/henrydate/vic-housing-data)**: Valuer-General suburb medians plus DFFH rents, with rental-yield decomposition, cash-rate sensitivity, and an interstate difference-in-differences on the 2024 VIC land-tax expansion, reported honestly as a null at the aggregate.
- **[qld-housing-data](https://github.com/henrydate/qld-housing-data)**: RTA bond-lodgement rents at suburb and postcode granularity plus an interactive postcode rent explorer (Excel); post-COVID rent-crisis and Brisbane-boom analysis.

### Earlier work
[Optimising_TA](https://github.com/henrydate/Optimising_TA) and [awhaleofaportfolio](https://github.com/henrydate/awhaleofaportfolio): earlier quantitative and FinTech projects (ensemble-ML signal testing; risk-weighted portfolio construction).

## Focus

**Valuation and modelling:** three-statement models, DCF with full WACC build, trading comparables, precedent transactions, sum-of-parts, scenario and sensitivity analysis, with a sourced and dated assumption trail behind every output.

**Fundamental research:** bottom-up company analysis, business-quality and competitive-moat assessment, investment-thesis construction.

**Data and tooling:** Python (Pandas, NumPy), web scraping (Playwright, BeautifulSoup), official-data ingestion (ABS SDMX, RBA, CKAN, RTA), resilient connector design, and applied econometrics (panel regressions, difference-in-differences).

## Toolbox

Excel (advanced) · Python (Pandas, NumPy) · SQL · Data Pipelines · DCF and Valuation Modelling · Financial Statement Analysis · PowerPoint

## Background

B.Com (Accounting) and B.Finance, Monash University · Monash/edX FinTech Boot Camp · CA Program (CA ANZ, in progress) · Accountant, Harlen Advisory · Equity Research Intern, Vachi Capital

## Contact

**[LinkedIn](https://www.linkedin.com/in/henry-date/)**: connect or send a DM, the fastest way to reach me.

Everything here is personal project work, shared to demonstrate analytical and technical capability. It is general information and educational material only, not financial product advice or a recommendation, and I am not licensed to provide financial advice. See individual repository disclaimers.

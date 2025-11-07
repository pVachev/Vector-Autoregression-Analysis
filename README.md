# Energy VAR Benchmark — Power, Gas, EUA (R)

Daily European power, gas and EUA time series. I ran ADF stationarity tests, Johansen cointegration, Granger causality and estimate VAR(p) on differenced series. I checked stability and summarize implications for co-movement across markets.

- **Report:** [`VAR_Project.html`](VAR_Project.html)
- **Tools:** R (`vars`, `urca`, `lmtest`), RMarkdown
- **Highlights:** strong two-way link between power and gas; EUA mostly follower in this dataset.

## Notes
Data sources and exact dates are described in the report. 

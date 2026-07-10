# Alex Biuckians — Data Science Portfolio

My personal portfolio site. M.S. Data Science candidate (George Washington University, May 2027), focused on decision modeling, forecasting, adversarial detection, streaming data engineering, causal / uplift modeling, and shipping models as deployed, tested services.

**Live site:** https://alexbiuckians.github.io/AlexBiuckiansPortfolioSite/

## About

A single-page site built from scratch with plain HTML, CSS, and vanilla JavaScript — no framework, no build step. It presents five flagship projects, a set of smaller projects, a skills overview, and contact details.

## Featured projects

- **Parquet Capital** — a front-office engine that prices NBA contracts as financial assets: quantile performance forecasts with calibrated uncertainty, then a decision-level backtest showing Overvalued flags cost ~8.6× more per delivered value point on held-out seasons. Built on 4,860 real player-seasons (scikit-learn, PuLP, Streamlit).
- **GridCast** — hourly electricity-load forecasting shipped like production software (LightGBM, FastAPI, MLflow, Docker, CI). Cut MAE 72% over a seasonal-naive baseline.
- **HouseEdge** — adversarial game-integrity detection using sequential hypothesis testing (SPRT/CUSUM) and anomaly detection, with a quantified detectability frontier and an honestly-exposed blind spot.
- **MacroQuant** — a real-time cross-asset streaming pipeline: two-lane tick ingestion across five asset classes, on-the-fly OHLCV resampling, live correlation, and GARCH + LSTM forecasts in a self-refreshing Dash dashboard.
- **UpliftIQ** — causal uplift-modeling API that targets *persuadable* customers rather than just high-risk ones (causalml, econml, FastAPI, deployed on Render).

Plus additional projects — retrieval-augmented Q&A over SEC filings (EdgarIQ), explainable healthcare fraud-risk prioritization (ClaimsGuard), and lung-cancer risk prediction (LungGuard) — on the live site.

## Built with

HTML · CSS · vanilla JavaScript · deployed on GitHub Pages

## Contact

- Email: alexbiuckians@gmail.com
- LinkedIn: https://www.linkedin.com/in/alex-biuckians/
- GitHub: https://github.com/alexbiuckians

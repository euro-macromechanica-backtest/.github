<div align="center">

# Euro Macromechanica (EMM) Backtesting Ecosystem

## Quantitative and macroeconomic FX research findings on EUR/USD price dynamics—demonstrated through transparent, reproducible backtests using the single model–EMM Quinta Medulla Invariance (M5 EMM core quant engine)—supported by a cryptographic audit trail and unedited, single-take live backtest runs.

> **A single fixed build of the M5 EMM engine (code and signal parameters) is applied uniformly across the entire backtest; no re-optimization or curve fitting is performed. The only variables are the cost model (commission, spread, slippage), the initial balance, and per-trade risk. GBP/USD cross-asset test is conducted with no parameter adjustments, covering 2008–August 2025, including Brexit 2016, to illustrate model robustness and absence of overfitting.**

**The backtest spans nearly the entire lifetime of the euro as the EU’s single currency (the euro was officially introduced in January 1999; euro banknotes and coins entered circulation in January 2002; retail FX brokers began offering EUR/USD in 2001).**

---

### Backtest periods per Data Quality Policy v1.0

**Core Baseline — 17 years 8 months**  
*Jan 1, 2008–Aug 31, 2025 (UTC+0, inclusive)*

**Extended Baseline — 5 years**  
*Jan 1, 2003–Dec 31, 2007 (UTC+0, inclusive)*

**Composite Baseline (Extended+Core) — 22 years 8 months**  
*Jan 1, 2003–Aug 31, 2025 (UTC+0, inclusive)*

**Stress — 2 years**  
*Jan 1, 2001–Dec 31, 2002 (UTC+0, inclusive)*

**GBP/USD Cross Asset Test — 17 years 8 months**
*Jan 1, 2008–Aug 31, 2025 (UTC+0, inclusive)*

---
### Total — 24 years 8 months  
### *Jan 1, 2001–Aug 31, 2025 (UTC+0, inclusive)*

</div>

---

## Quick links

<div align="center">

### Euro Macromechanica (EMM) Research https://emmresearch.github.io

### ‼️ MUST READ — Euro Macromechanica (EMM) Backtest — Overview & Methodology: main [results/README.md](https://github.com/euro-macromechanica-backtest/results/blob/main/README.md) · ru: [results/README.ru.md](https://github.com/euro-macromechanica-backtest/results/blob/main/README.ru.md)

**Euro Macromechanica (EMM) Backtest — Overview & Methodology — web page version:** https://euro-macromechanica-backtest.github.io

</div>

- 🔎 **Audit guide:** [`AUDIT.md`](https://github.com/euro-macromechanica-backtest/results/blob/main/docs/AUDIT.md) · **ru:** [`AUDIT.ru.md`](https://github.com/euro-macromechanica-backtest/results/blob/main/docs/AUDIT.ru.md)
- 🧾 Integrity guide (SHA-256, GPG, OTS): [`INTEGRITY.md`](https://github.com/euro-macromechanica-backtest/results/blob/main/docs/INTEGRITY.md) · **ru:** [`INTEGRITY.ru.md`](https://github.com/euro-macromechanica-backtest/results/blob/main/docs/INTEGRITY.ru.md)
- 📈 Results and metrics for each track and mode: [`results/`](https://github.com/euro-macromechanica-backtest/results/tree/main/results)
- 🎥 Live backtest runs: see the **Overview & Methodology**.

For input ↔ result pinning and provenance, see:
- 📊 Results: [`INPUTS-PIN.md`](https://github.com/euro-macromechanica-backtest/results/blob/main/docs/INPUTS-PIN.md) · **ru:** [`INPUTS-PIN.ru.md`](https://github.com/euro-macromechanica-backtest/results/blob/main/docs/INPUTS-PIN.ru.md)
- 🗄️ Data Hub: [`INPUTS-PROVENANCE.md`](https://github.com/euro-macromechanica-backtest/data-hub/blob/main/INPUTS-PROVENANCE.md) · **ru:** [`INPUTS-PROVENANCE.ru.md`](https://github.com/euro-macromechanica-backtest/data-hub/blob/main/INPUTS-PROVENANCE.ru.md)

## 📦 Repositories

- 📊 Results: https://github.com/euro-macromechanica-backtest/results  
- 📦 Data Hub: https://github.com/euro-macromechanica-backtest/data-hub  
- 🧪 Data Preparation Toolkit: https://github.com/euro-macromechanica-backtest/data-preparation-toolkit 
- 📈 Metrics Toolkit: https://github.com/euro-macromechanica-backtest/metrics-toolkit

## 🔒 Proprietary strategy code

- The M5 EMM engine is **proprietary** and **not published** in this ecosystem.
- No **fundamental algorithmic details/raw parameter dumps** are publicly disclosed.
- Strategy proof of existence is provided via **SHA-256 hash, GPG signature, and OTS anchor** for the exact engine build used across all backtests (see [`results/strategy_existence_evidence`](https://github.com/euro-macromechanica-backtest/results/tree/main/strategy_existence_evidence)).
- Reproducibility is demonstrated through:
  - **Live backtest runs** (unedited videos) with matching integrity artifacts.
  - **Input ↔ result pinning** (see the **Quick links** section above).

## ✅ GPG signature & fingerprint

Public key in the **results** repo: [`keys/emm_pub_key.asc`](https://github.com/euro-macromechanica-backtest/results/blob/main/keys/emm_pub_key.asc) (ASCII-armored)  
**GPG key fingerprint (rleydev — thelaziestcat):** `4E53 DA03 D1A1 644E 6479  3C47 EEEC 0AFA 4D8A F0A7`

## 📎 License

See the individual repositories.

## ⚠️ Disclaimer — Not Investment Advice

This material is provided for informational and research purposes only and does not constitute investment advice, an offer, or a solicitation. Backtested results are hypothetical and subject to limitations; past performance is not indicative of future results. Assumptions (cost models, risk, etc.) are illustrative and may not align with the reader’s objectives or constraints.
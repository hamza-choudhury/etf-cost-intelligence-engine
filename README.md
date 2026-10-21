# ETF Cost Intelligence Engine

## Complete Feature Set

### Core Analytics
* **Six-Provider Comparison**: Deep-dive comparison of the S&P 500 UCITS ETF across BlackRock (iShares), State Street (SPDR), Vanguard, Xtrackers (DWS), Amundi, and Invesco.
* **Cost and Scale Metrics**: Extraction and ranking of TER (basis points), AUM (USD billions), holdings count, and SRRI risk indicator for each fund.
* **Composite Efficiency Labels**: Identifies the cost leader, scale leader, and balanced funds across the set.
* **Narrative Generation**: Plain-text interpretation of the central finding (cost leadership and scale leadership sit in different providers).

### Product Characteristics
* **Replication Method**: Physical vs. synthetic classification for each fund.
* **Distribution Policy**: Accumulating vs. distributing share classes (Amundi is the sole distributing fund).
* **Inception Date and Listing**: Fund age and primary exchange.

### Technical Implementation
* **Python and Pandas**: Structured comparison DataFrame with 1-based ranks and validation bounds.
* **Plotly Visualisation**: Three interactive charts (TER bar, AUM bar, TER vs AUM scatter) embedded in a self-contained HTML dashboard.
* **Source Traceability**: Every fund links directly to its webpage, KIID, and factsheet for easy fact-checking.
* **Self-Contained Output**: Single `etf_dashboard.html` file with no server dependency, styled with CSS for a clean, professional UI.

### Output Files
1. `etf_dashboard.html` — Self-contained dashboard with KPI tiles, charts, comparison table, and narrative.
2. `ETF_Cost_Intelligence_Engine.ipynb` — Jupyter notebook with the full data pipeline and analytics.

---

**Source Code:** github.com/hamza-choudhury/etf-cost-intelligence-engine

*Educational tool demonstrating ETF product knowledge, competitive intelligence, and Python data analysis.*

---

### Support the Project
If you found this useful, you can support my work here:
* ☕ [Buy Me a Coffee](https://buymeacoffee.com/hchoudhury)
* 💙 [PayPal](https://www.paypal.com/paypalme/HChoudhury0)

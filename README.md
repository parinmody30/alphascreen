# AlphaScreen

Equity screening platform. Feed it a CSV/XLSX of stock metrics and it builds a self-contained, dark-themed HTML research dashboard:

- 7-factor scoring: Quality, Growth, Valuation, Safety, Cash Flow, Ownership, Momentum
- Investment, Risk, Confidence and Opportunity scores
- Rule-based investment theses and a red-flag engine
- Sector analytics and multi-company comparison
- CSV / Excel / PDF export from inside the dashboard

## Usage

**Google Colab:** paste `alphascreen.py` into a cell and run it; you'll be prompted to upload your file.

**Locally:** install dependencies, set `CSV_PATH` at the top of `alphascreen.py` to your data file, run it, then open `equity_research_dashboard.html` in a browser.

```bash
pip install -r requirements.txt
```

```bash
python alphascreen.py
```

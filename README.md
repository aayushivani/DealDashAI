DealDashAI is a browser-based financial modeling app that lets you type plain-English scenarios
(e.g., “drop EBITDA margin 200 bps and raise rates 50 bps”) and instantly see:

- Enterprise Value, Equity Value, and per-share outputs  
- Leverage and interest-coverage metrics  
- Sensitivity heatmaps and EV bridge waterfall  
- Cap-table modeling (primary/secondary raises, option pool)  
- Optional Monte-Carlo simulations of equity per share

Tech stack
- Python for the valuation engine
- Streamlit for the interactive UI
- Plotly for charts and visualizations
- Pandas & NumPy for data handling

### Run locally
```bash
pip install -r requirements.txt
streamlit run main.py

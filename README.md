# PAXG SMC Mini App

A complete client-side Telegram Mini App for PAXG/USDT SMC and price-action analysis. Built as a single static `index.html` file with:

- Telegram WebApp SDK integration
- Dark Gold & Charcoal trading theme
- Live PAXG/USDT real-time data from Binance REST + WebSocket
- 15m / 1H / 4H timeframe switching
- TradingView Lightweight Charts candlesticks
- AI signal generation via Google Gemini API
- Entry / Stop Loss / TP price lines on the chart
- Signal summary card with risk-to-reward and reasoning
- Telegram send / copy signal actions
- Mobile-first responsive layout for GitHub Pages

## Run locally

Open `index.html` in a browser, or use a tiny local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Settings

Open the Settings modal and save your Google Gemini API key in browser `localStorage` before running an analysis.

## Note

This is a client-side app designed for demo and educational use. It is not financial advice.

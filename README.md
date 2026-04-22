# Value Investor Agent

A free, open-source value investing tool that runs entirely in your browser.

## Features
- 📐 Graham deep value screener (PE≤9, PB≤1.9, PE×PB≤22.5) — US + Nordic stocks
- ✨ Magic Formula screener (Earnings Yield + Return on Capital)
- ⭐ Combined shortlist — stocks passing both strategies
- 📊 Live market dashboard — 6 global indices, Buffett Indicator, breadth indicators
- 💼 Portfolio tracker — live prices, gain/loss, day change
- 📈 Full technical analysis — RSI, MACD, Bollinger Bands, Stochastic, ATR
- 🔔 VIX and RSI alarm bells
- 🤖 AI advisor powered by Claude

## Setup
1. Get a free **Finnhub API key** at [finnhub.io](https://finnhub.io) (for live index prices)
2. Get an **Anthropic API key** at [console.anthropic.com](https://console.anthropic.com) (for AI features — ~$2–3/month)
3. Open the site, paste both keys into the fields at the top — they save in your browser

## Hosting on GitHub Pages
1. Fork this repository
2. Go to Settings → Pages → Deploy from main branch
3. Your site is live at `https://yourusername.github.io/repository-name`

## Privacy
Your API keys are stored only in your browser's localStorage. They are sent directly to Anthropic and Finnhub — never to any third-party server.

## Disclaimer
For educational purposes only. Not financial advice. Always verify data with live sources before making investment decisions.

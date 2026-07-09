# Quant Edge Solutions (QES)

**We don't only trade Red folder events. We also fade the Algo behind the orange ones.**

---

## 🎯 What Is QES?

QES is a proprietary news-trading framework built by Leon — a trader since 2014 — in collaboration with AI (Claude, DeepSeek). It transforms economic data releases into precise, low-risk trade entries with institutional-grade execution.

---

## 📦 Product Suite

| System | Focus |
|--------|-------|
| **CPI Edge Premium** | US/EZ CPI releases |
| **NFP Edge** | Non-Farm Payrolls |
| **Central Banks Edge** | Rate decisions & speeches |
| **Jobless Claims Edge** | Weekly claims data |
| **FibVCP / WickPrint** | Micro-systems for intraday precision |

---

## 🧠 Core Philosophy

- **Orange- folder events (EZ, JP, CH)** produce cleaner, higher-win-rate setups than red events.
- **Entry protocol:** H1 candle close for EZ/Asia; 15-min wait for US releases (14:30 SAST).
- **Risk:** 1% per trade ($1,000 per $100k), 25-pip SL, max 2 losses/day.
- **VIX filter:** <25 only.

---

## 📊 Live Competition

This system is currently being battle-tested live in the **Top One Trader "Battle for the Belt"** — a $100k account, trading from July 6–17, 2026.

All trades are logged transparently.

---

## 🛠️ Tech Stack

- Python (backtesting & signal generation)
- Google Sheets API (trade logging)
- TradingView (chart execution)

---

## 📈 Example Trade (Live Simulation)

**Event:** Eurozone Flash CPI (Actual 2.8% vs Forecast 3.0% — MISS)

**System:** Contrarian SHORT on EUR/USD

**Entry:** 1.13966 (H1 close)

**Result:** TP1 (+15 pips), TP2 (+25 pips) → **+20 pips avg / +$400 per lot**

---

## 🚀 Getting Started

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Configure your API keys (see `.env.example`)
4. Run backtests: `python backtest.py --system CPI`

---

## 📬 Connect

- **X (Twitter):** [https://x.com/leonjonas407
- email- leonjonas407@gmail.com

## 📝 License

Proprietary — all rights reserved. QES is not open-source for commercial use.

---

*Built with discipline. Traded with precision.*

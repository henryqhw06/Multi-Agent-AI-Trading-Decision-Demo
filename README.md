# CryptoMind AI
### Multi-Agent AI Trading Decision Demo

CryptoMind AI is a frontend demonstration project that showcases a multi-agent AI decision-making workflow for cryptocurrency market analysis.  
The system simulates how a quantitative trading desk integrates technical analysis, risk control, and managerial decision layers to produce structured trading decisions.

> Demo only · Research & educational purpose · Not financial advice

---

## Key Features

- **Multi-Agent Architecture**
  - Layer 1: Analysts (Scalper / Trend / Quant / On-chain / Macro)
  - Layer 2: Managers (Technical Director & Fundamental Director)
  - Layer 3: Risk Control (Rule-based + AI review)
  - Layer 4: CEO (Final structured JSON decision)

- **Real-time Market Visualization**
  - 1-minute K-lines from Binance (last 60 candles)
  - Indicators: MA7 / MA25 / Bollinger Bands / RSI / Volatility
  - Interactive chart powered by ECharts

- **Risk-Aware Decision Logic**
  - Stop-loss / Take-profit estimation
  - Risk-reward (R:R) gating
  - Configurable risk profiles (Aggressive / Moderate / Conservative)

- **Structured Output**
  - Machine-readable JSON decision output
  - Includes confidence, regime, position size, and scenario analysis

- **Decision Memory**
  - Local decision history stored in browser (no backend)

---

## System Architecture

```text
Market Data (Binance)
        ↓
Indicator & Regime Detection
        ↓
Layer 1: Analysts (Parallel Reasoning)
        ↓
Layer 2: Managers (Technical & Fundamental Integration)
        ↓
Layer 3: Risk Control (Rules + AI Review)
        ↓
Layer 4: CEO Decision (Structured JSON Output)

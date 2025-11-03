# 🤖 Galantis - Automated Trading System

> **Automated perpetual futures trading bridge** connecting TradingView alerts with Asterdex exchange execution

![System Status](https://img.shields.io/badge/status-production-brightgreen)
![Trading Mode](https://img.shields.io/badge/mode-perpetuals-blue)
![Margin Type](https://img.shields.io/badge/margin-isolated-orange)
![Project](https://img.shields.io/badge/project-galantis-purple)

---

## 🎯 What Galantis Does

**Galantis** is an automated trading bridge that enables seamless execution of TradingView strategy signals on Asterdex Perpetuals exchange:

1. **Receives trading alerts** from TradingView (custom Pine Script strategies)
2. **Validates and authenticates** incoming webhooks with HMAC security
3. **Automatically executes trades** on Asterdex with proper risk management
4. **Manages positions** with configurable leverage and margin settings

### Key Capabilities

- ✅ **Real-time Execution**: Sub-second trade placement from alert to exchange
- ✅ **USDT Position Sizing**: Specify size in USDT, automatic conversion to asset quantity
- ✅ **Leverage Trading**: Support for 1x-20x leverage on perpetual contracts
- ✅ **Isolated Margin**: Independent margin per position to limit risk exposure
- ✅ **One-Way Mode**: Compatible with standard position mode (BUY/SELL via BOTH side)
- ✅ **Market Orders**: Instant execution at current market price
- ✅ **Position Control**: Open, add to, and close positions via reduce-only flag
- ✅ **Security**: Webhook secret validation and API signature authentication

---

## 📚 Documentation

### Core Documentation

- **[📊 SYSTEM_FLOW.md](SYSTEM_FLOW.md)** - Complete execution flow from alert to trade
- **[📡 TRADINGVIEW_ALERTS.md](TRADINGVIEW_ALERTS.md)** - Alert structure and examples
- **[🎨 dashboard.html](dashboard.html)** - Interactive visual dashboard of system logic

### Additional Resources

- **[POSITION_SIZE_CALCULATOR.md](POSITION_SIZE_CALCULATOR.md)** - Position sizing guide with examples

---

## 🏗️ System Architecture

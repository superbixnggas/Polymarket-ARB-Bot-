# Polymarket BTC Arbitrage Bot

A monitoring platform that demonstrates how a trading bot scans BTC prediction markets and detects arbitrage opportunities on Polymarket.

## Overview

This project provides a web-based simulation dashboard that shows how an arbitrage bot monitors BTC 5-minute prediction markets on Polymarket and detects pricing inefficiencies between YES and NO positions.

## Features

- **Live BTC Price Monitoring** - Real-time BTC price from CoinGecko API
- **Arbitrage Detection** - Monitors YES/NO price spreads
- **Bot Activity Logs** - Terminal-style logs showing bot operations
- **Market Analysis** - Real-time market data display
- **Simulation Controls** - Start, Pause, and Clear simulation

## Web Interface

The project includes two main pages:

### 1. Landing Page (landing.html)
Modern crypto-style entry page with:
- Animated gradient backgrounds
- Project preview card
- Navigation to dashboard

### 2. Simulation Dashboard (simulation.html)
Full bot monitoring dashboard with:
- Live BTC price display
- Bot status and statistics
- Market analysis panel
- Terminal-style activity logs
- Start/Pause/Clear controls

## How It Works

The simulation monitors BTC 5-minute prediction markets and detects arbitrage opportunities when:

- YES price + NO price < 0.97

When an arbitrage opportunity is detected, the bot logs the opportunity and calculates estimated profit.

## Usage

Simply open the HTML files in a web browser:

- `landing.html` - Entry page
- `simulation.html` - Main dashboard

## Technologies

- HTML5
- CSS3 (Dark theme with neon accents)
- JavaScript (Simulation logic)
- CoinGecko API (Live BTC prices)

## License

MIT License

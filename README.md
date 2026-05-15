# Smart Money Tracker

A personal stock market dashboard that tracks smart money (13F filings, congressional trades) and combines them with live price action signals to produce conviction scores.

## Pages

- **[Dashboard](index.html)** — main smart money tracker with live Finnhub data
- **[Simulation](simulation.html)** — daily automated trading simulation tracker

## Setup

Both pages require a free [Finnhub API key](https://finnhub.io/register) — enter it on first load.

## Features

- Live stock prices via Finnhub (~15 min delay on free tier)
- 13F smart money overlap scoring (Buffett, Pelosi, Ackman, Tepper, Druckenmiller)
- 200-day moving average + 52-week high from 400 days of candle history
- OBV (On-Balance Volume) accumulation detection
- Next Nvidia detector scoring future breakout candidates
- Quantum computing + Future energy investment analysis
- Freetrade portfolio import with live P&L
- Buy/Sell/Hold signals on all holdings
- Wealth management plan with projections
- Light/dark mode

## Data sources

- Price data: [Finnhub](https://finnhub.io) (free tier)
- 13F filings: Seeded from public SEC EDGAR data
- Congressional trades: Seeded from public eFD disclosures

> Not financial advice. Past performance does not predict future results.

# Relationship to Premia

## Purpose of each package
premia: pricing, greeks, financial primitives

hedgesim: simulation, backtesting, hedging workflows

## Dependency direction
hedgesim depends on premia, but not vice versa

## What goes where

| Task / Concept            | Goes in  |
| ------------------------- | -------- |
| Black-Scholes pricing     | premia   |
| Greeks calculation        | premia   |
| Path simulation           | hedgesim |
| Hedging strategy logic    | hedgesim |
| PnL attribution over time | hedgesim |


## Open questions
# latam-fx-macro-dashboard

A simple macro dashboard for tracking major Latin American currencies against the main global drivers that usually matter for them.

It compares where EM FX is trading to what macro suggests it should be doing. If there’s a gap, that flags potential relative value or positioning opportunities.

## What data it uses

- **FRED**
  - US 10Y Treasury yield
  - US 2Y Treasury yield
  - broad dollar index proxy

- **Alpha Vantage**
  - USD/MXN
  - USD/BRL
  - USD/COP
  - USD/CLP
  - USD/PEN
  - WTI crude oil
  - copper

## What each section does

- **Top strip**  
  Shows the latest FX levels and the latest macro markets in one line.

- **LatAm FX vs USD table**  
  Shows each currency’s daily move, a simple macro score, the gap between price action and macro, and a plain English read on whether the move looks in line or out of line.

- **Key Macro Drivers**  
  Shows the latest levels and daily moves in US yields, the dollar proxy, oil, copper, and the yield curve.

- **FX / Macro Correlation**  
  Uses recent real returns to show how each currency has been moving against the dollar, yields, oil, and copper.

- **DXY Proxy vs LatAm FX chart**  
  Compares the recent path of the broad dollar index proxy with selected LatAm FX pairs.

- **Macro Gap Heatmap**  
  Highlights where FX looks stronger or weaker than the macro backdrop would suggest.

- **Signals**  
  Summarises each currency in plain English using the main drivers and the current macro gap.

- **US Treasury Yields and Commodity Prices**  
  Adds broader context for rates and commodity support.

## Notes

This is a macro monitoring tool, not a full trading system.  
It is designed to organise macro information in a cleaner and more structured way.

Please note that with a Live API paid service, this could be transformed into fully functional. Consider this as a demo concept using free data.

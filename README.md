# latam-fx-macro-dashboard

This is a simple macro dashboard for tracking how major Latin American currencies are behaving relative to key global drivers.

Instead of just showing FX moves, it tries to answer a more useful question:

"Are these currencies moving in line with macro conditions, or is something mispriced?"

## What it covers

The dashboard tracks:

- Latin American currencies:
  - Mexican Peso (MXN)
  - Brazilian Real (BRL)
  - Colombian Peso (COP)
  - Chilean Peso (CLP)
  - Peruvian Sol (PEN)

- Key macro drivers:
  - US Dollar index (DXY)
  - US interest rates (2Y and 10Y Treasury yields)
  - Oil (important for MXN and COP)
  - Copper (important for CLP and PEN)

## What it shows

- Live FX rates and daily moves  
- A macro score that reflects how supportive global conditions are for EM FX  
- A mispricing measure showing whether FX has moved more or less than macro would suggest  
- A correlation view of how each currency relates to DXY, yields, and commodities  
- A signal panel highlighting potential long, short, or neutral setups  

## What the idea is

The goal is not to predict prices perfectly.

It is to:
- identify when macro conditions are clearly supportive or negative  
- spot when FX is not reacting as expected  
- highlight potential relative value or risk asymmetry  

## Notes

This is a prototype built as a single-page browser dashboard.  
Some components use simplified assumptions and should be treated as indicative rather than fully model-driven.

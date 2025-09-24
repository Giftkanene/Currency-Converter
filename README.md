# Currency Converter

this converts an amount between two currencies using real time exchange rates from exchangerate-api.com.

## Features
- Convert between two selected currencies using live rates.
- Instant conversion as you type.
- Swap currencies with one click.
- No build tools required — pure HTML/CSS/JS.

## How to run
1. Open the project folder in your editor.
2. Open `index.html` in a browser, or serve the folder and visit the local server:
   - Using Python (Windows): `py -m http.server 8000` then open http://localhost:8000
3. Ensure you have an internet connection (the app fetches rates from exchangerate-api.com).

## How it works (brief)
- script.js fetches latest rates for the selected base currency from https://api.exchangerate-api.com/v4/latest/{BASE}.
- The chosen target currency rate is applied to the entered amount and the result is displayed with two decimals.
- Event listeners:
  - currency selects and amount input trigger recalculation.
  - swap button swaps the two selected currencies and recalculates.
- The UI shows the current exchange rate (e.g. "1 USD = 0.85 EUR").

## Authors
- [@octokatherine](https://github.com/Giftkanene)




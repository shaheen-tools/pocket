# Pocket Tool

A small set of everyday tools in one web page: split a bill, convert units, date maths, percentages, QR codes, time zones, passwords, price comparison (with photo scan), VAT, a calculator, currency conversion and a checklist.

Open `index.html` in a browser. On GitHub Pages: https://shaheen-tools.github.io/pocket/

Notes:
- Currency rates: the page loads live rates when online. A GitHub Action (`.github/workflows/update-rates.yml`) also saves them daily to `rates.json`, which the page uses as a fallback. The newest source wins, and you can still type your own rates. Rates are from [ExchangeRate-API](https://www.exchangerate-api.com).
- The checklist is saved in the browser on that device only.
- QR codes and the price-tag photo reader load small libraries from cdnjs, so they need an internet connection.

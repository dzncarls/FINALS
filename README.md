# Porac Pricing DSS

A self-contained local dashboard for monitoring agricultural commodity prices, market movement, and regional signals.

## Run without npm

You can launch this app directly in a browser without installing Node or running any package manager.

Option 1: open the file directly
- Double-click `index.html`, or
- open it from your browser via File > Open

Option 2: use the included helper script
- On Windows, run `run.bat`

For the mobile entry point, open `mobile.html`. It uses the same dashboard logic as `index.html` and lets the existing responsive layout adapt to the device width without maintaining a second copy of the app.

For the farmer-perspective view of the same DSS, open `farmer.html`. It keeps the Porac prices, market trends, weather, transactions, and local Price Outlook, while presenting the dashboard as a farmer workspace instead of an administrator workspace.

The HTML entry points use local files and work without npm or external add-ons.

## Included

- Overview KPI cards for price, volume, markets, and alerts
- Talong and Patani crop, region, and time-period filters
- Both crops listed at all four markets, with distinct sample prices per market
- Eight-month price movement chart
- Regional price comparison
- Filterable market watchlist with status signals
- Local price-direction outlook using stored price trends, market changes, listing availability, and the sample local weather outlook
- Local SVG charts for monthly price history, the estimated next price, and each factor's forecast contribution
- All-crops outlook slideshow with manual controls; selecting a crop pins its graph, and community filtering remains available
- Responsive desktop and mobile layout

The current data is representative sample data. Only Talong and Patani are included in the crop listings and farmer profiles. The Price Outlook is calculated in the browser from those local records using a transparent rule-based estimate; it does not use a network connection, external service, or trained forecasting model. No npm, Node.js, or external dependencies are required.

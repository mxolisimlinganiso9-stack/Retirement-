# XAUUSD M5 iPad Easy Edition

Upload these 4 files to the TOP LEVEL of a GitHub repository:
package.json
server.js
render.yaml
README.md

Render:
Root Directory: leave blank
Build Command: npm install
Start Command: npm start
Health Check: /api/health

It starts in demo mode. For real XAU/USD candles, set MARKET_DATA_PROVIDER=twelvedata and add your private MARKET_DATA_API_KEY in Render Environment. Never put the key in GitHub or chat.

This is paper trading only; it sends no real broker orders.

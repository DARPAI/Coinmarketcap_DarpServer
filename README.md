# Coinmarketcap DARP Server 📊

A DARP server that provides CoinMarketCap API .

### Getting Started 🚀
This program uses uv for package management https://docs.astral.sh/uv

### Environment Setup ⚙️

1. Install uv:
```bash
pip install uv
```

2. Install dependencies:
```bash
uv pip install -r requirements.txt
```

3. Configure API Key:
Create a `.env` file and add:
```
COINMARKETCAP_API_KEY=your-api-key-here
```

4. Run the server:
```bash
uv run ./src/coin_api_mcp/server.py
```

### Available API Tools 🛠️

1. `listing-coins` - Returns a list of all active cryptocurrencies with latest market data
   - Supports filtering by price, market cap, volume, supply, and more
   - Customizable sorting and pagination
   - Optional currency conversion

2. `get-coin-info` - Get detailed cryptocurrency information
   - Logo, description, website URLs, social links, technical documentation
   - Support lookup by ID, slug, symbol or contract address
   - Customizable auxiliary data fields

3. `get-coin-quotes` - Get latest market quotes
   - Support for multiple cryptocurrencies in one call
   - Multiple fiat/crypto currency conversion
   - Extensive market data including price, volume, supply metrics

### Server Details 🖥️

- Default host: 0.0.0.0
- Default port: 3000


---

# cointelPY
![Alt text](https://raw.githubusercontent.com/cointelfinance/cointelR/master/figures/logo.png?raw=true "Title")

# Load Dependencies
```python
import pandas as pd
```
# Package Functions
```python
cointel_api_url = "https://cointel-api.herokuapp.com/wallet_balances?wallet_address=0xe83b691f8E42D86cDa0c2D7fB62Ce5f562d5Af41"
cointel_wallet_balances = pd.read_csv(cointel_api_url)
```
# Products & Lifecycles
| Product | Description | Product Lifecycle |
|---|---|---|
| [cointel-api](https://cointel-api.herokuapp.com/__docs__/) | 💡 Cointel's Free Api | production |
| [cointel-app](https://github.com/cointelfinance/cointel-api) | ⏬ Cointel's App | beta |
| [request-cointel](https://github.com/cointelfinance/request) | ✅ Request a Cointel Account | production |

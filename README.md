# BscScan

BscScan is the leading block explorer and analytics platform for BNB Smart Chain (BSC). It provides a REST API for querying on-chain data including account balances, transactions, BEP-20 and BEP-721 token transfers, smart contract ABIs and source code, event logs, gas prices, block data, and network statistics.

API subscriptions are now unified under the Etherscan V2 platform, granting access to 60+ EVM chains via a single API key. BNB Smart Chain is accessed using `chainid=56` in API requests.

## Base URL

```
https://api.bscscan.com/v2/api
```

## Authentication

All requests require an API key. Create a free key at [bscscan.com/myapikey](https://bscscan.com/myapikey) after registering an account.

```
?apikey=YOUR_API_KEY&chainid=56
```

## API Modules

| Module | Description |
|--------|-------------|
| Accounts | BNB balances, normal transactions, internal transactions, BEP-20 and BEP-721 token transfers, validated blocks |
| Blocks | Block rewards, block number by timestamp, estimated block countdown |
| Contracts | Contract ABI, verified source code retrieval |
| Logs | Filtered event log queries across block ranges |
| Proxy | JSON-RPC proxy for block number, block data, transactions, gas price, contract calls |
| Stats | BNB last price, total BNB supply, validators list |
| Tokens | Token supply, circulating supply, account token balances by contract address |
| Transactions | Transaction receipt status verification |

## Plans

| Plan | Price/month | Rate Limit | Daily Calls |
|------|-------------|------------|-------------|
| Free | $0 | 5 calls/sec | 100,000 |
| Lite | $49 | 5 calls/sec | 100,000 |
| Standard | $199 | 10 calls/sec | 200,000 |
| Advanced | $299 | 20 calls/sec | 500,000 |
| Professional | $399 | 30 calls/sec | 1,000,000 |
| Pro Plus | $899 | 30 calls/sec | 1,500,000 |
| Enterprise | Custom | Unmetered | Unmetered |

## Links

- [Website](https://bscscan.com)
- [API Documentation](https://info.bscscan.com/apis/)
- [API Key Management](https://bscscan.com/myapikey)
- [Pricing](https://etherscan.io/apis?id=56)
- [Terms of Service](https://bscscan.com/terms)

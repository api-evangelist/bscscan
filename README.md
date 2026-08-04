# BscScan

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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

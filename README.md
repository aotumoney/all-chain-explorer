# All-Chain Explorer

A multi-chain block explorer for TRON, Ethereum, Bitcoin and Solana — with USDT freeze checks, transfer-fee estimates, address risk signals and a Telegram alert bot.

- Website: https://chianbot66.cc
- API docs: https://chianbot66.cc/api-docs
- Telegram bot: https://t.me/dfdshagent_bot
- Telegram channel: https://t.me/chain66bot

## What it does

- **TRON / Ethereum / Bitcoin / Solana** block, transaction and address lookup
- **USDT blacklist search** for TRON and Ethereum (Tether freeze status)
- **Transfer fee estimator** using live chain parameters
- **Address risk signals** from GoPlus plus local Tether freeze data
- **Notable wallets** page with publicly verifiable addresses: https://chianbot66.cc/wallets/famous
- **Telegram bot** for TRON address monitoring and price alerts: https://t.me/dfdshagent_bot

## Public API (free tier)

| Endpoint | Description |
|---|---|
| `GET /api/trx/address/{address}` | TRON account overview |
| `GET /api/trx/blacklist` | Tether USDT freeze list (TRON) |
| `GET /api/eth/address/{address}` | Ethereum account overview |
| `GET /api/eth/blacklist` | Tether USDT freeze list (Ethereum) |

Free tier: 60 requests/minute, 2,000/day. Pro and Business tiers available.

## Stack

Zero-dependency Node.js, nginx, systemd, Cloudflare. Data from TronGrid, public Ethereum RPC, mempool.space, Solana RPC and GoPlus. No cookies, no third-party analytics.

## Links

- Guides: https://chianbot66.cc/guides
- Pricing: https://chianbot66.cc/pricing
- Contact: https://chianbot66.cc/contact

Independent project, not affiliated with Tether, Binance or any exchange.

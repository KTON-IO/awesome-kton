# Awesome KTON: The Ultimate Resource for KTON and Liquid Staking on TON

A curated list of awesome KTON resources, tools, and services for the TON ecosystem.

## Contents

- [Overview](#overview)
- [Official Resources](#official-resources)
- [Smart Contracts](#smart-contracts)
- [DeFi Integrations](#defi-integrations)
- [Developer Resources](#developer-resources)
- [TON Ecosystem Tools](#ton-ecosystem-tools)
- [Community & Social](#community--social)
- [Media Kit](#media-kit)
- [Comparisons](#comparisons)

## Overview

**KTON** is a liquid staking protocol on TON. Stake TON and receive the liquid staking token $KTON, which earns validator rewards; to get TON back, redeem KTON through the pool.

## Official Resources

- [Website](https://kton.io/) - Official KTON website
- [dApp](https://app.kton.io/) - KTON web application
- [Telegram Mini App](https://t.me/ktonio_bot) - KTON Telegram bot
- [TON App Listing](https://ton.app/staking/kton-lst?id=4695) - KTON on TON Apps
- [Medium Blog](https://medium.com/kton-io) - KTON blog posts
- [Documentation](https://docs.kton.io/) - KTON documentation

## Smart Contracts

- **Contract Address:** `EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw`
- **Icon:** [https://app.kton.io/logo-256x256.png](https://app.kton.io/logo-256x256.png)
- [TON Viewer](https://tonviewer.com/EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw) - View on TON Viewer
- [TONScan](https://tonscan.org/jetton/EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw) - View on TONScan
- [GitHub Repository](https://github.com/KTON-IO/liquid-staking-contract) - Open source contracts
- [Audit Report](https://github.com/KTON-IO/liquid-staking-contract/blob/v2/KTON-Final-Audit-Report.pdf) - Security audit

**Token Metadata** ([app.kton.io/jetton-metadata.json](https://app.kton.io/jetton-metadata.json), the URI stored in the jetton master `0:6e2215cd36459ff405bd9a234635348efee159db77a37c85ab89e5e07b97fbdf`):
```json
{
  "name": "KTON",
  "description": "KTON, The Liquid Staking Token of TON.",
  "symbol": "KTON",
  "decimals": 9,
  "image": "https://app.kton.io/logo-256x256.png"
}
```

## DeFi Integrations

### Turning KTON back into TON
- [Withdraw in the dApp](https://app.kton.io/) - Redeem KTON through the pool at its own rate: **Withdraw now** pays at once from the pool's idle balance for the instant-withdrawal fee (0.2% as of November 2026, shown before you sign), or wait for the next rotation and pay no fee.
- Please do not sell KTON on a DEX. DEX pools set their own price for KTON, and it has been well below the pool's rate: on 2026-11-05 selling on STON.fi paid about 6% less than redeeming.

### Market Data
- [CoinGecko](https://www.coingecko.com/en/coins/kton-staked-kton) - KTON price data
- [DeFiLlama](https://defillama.com/protocol/kton) - KTON TVL

## Developer Resources

- [KTON-IO Organization](https://github.com/KTON-IO) - GitHub organization
- [KTON Documentation](https://docs.kton.io/) - Developer documentation

## TON Ecosystem Tools

### Wallets
- [Keeper](https://keeperwallet.com/) (formerly Tonkeeper) - Self-custodial wallet
- [My Wallet](https://mywallet.io/) (formerly MyTonWallet) - Self-custodial wallet
- [iMe](https://imem.app/) - Multi-chain wallet with TON support
- [Bitget Wallet](https://web3.bitget.com/) - Multi-chain wallet with TON support
- [Tonhub](https://tonhub.com/) - Native TON mobile wallet
- [Ledger](https://www.ledger.com/) - Hardware wallet with TON support

### Block Explorers
- [Tonviewer](https://tonviewer.com/) - Comprehensive TON blockchain explorer
- [Tonscan](https://tonscan.org/) - Advanced TON blockchain analytics
- [DYOR.io](https://dyor.io/) - DeFi analytics and portfolio tracking
- [OKX Explorer](https://web3.okx.com/explorer/ton) - OKX's TON explorer
- [Dton](https://dton.io/) - TON blockchain data analytics

### DEXs
- [STON.fi](https://app.ston.fi/) - Leading TON decentralized exchange
- [DeDust.io](https://dedust.io/) - TON-based decentralized exchange
- [TONCO](https://tonco.io/) - TON decentralized exchange
- [Titan](https://titan.trade/) - TON trading platform
- [Swap Coffee](https://swap.coffee/) - TON trading platform

### App Discovery
- [TON Apps Center](https://ton.app/) - Official TON applications directory
- [Pyth](https://pyth.network/) - Price oracle network for TON DeFi

## Community & Social

- [Telegram Group](https://t.me/kton_group) - KTON community group
- [Telegram Channel](https://t.me/kton_channel) - KTON announcements
- [Twitter/X](https://x.com/kton_io) - KTON official Twitter

## Media Kit

- [KTON Media Kit](https://kton.io/media-kit/) - Logos, colours, naming and key facts
- [KTON Public Deck](https://docsend.com/v/tny7v/kton_public) - Public presentation deck

## Comparisons

| Feature | KTON | Protocol B | Protocol C |
|---------|------|------------|------------|
| Architecture | LST V2 (modular) | LST V1 | Pool-based |
| Minimum Stake | 1 TON | 1 TON | 50 TON |
| Instant Withdrawals | Smaller amounts, 0.2% fee, from the pool's idle balance | Yes | Yes |
| Security Audit | TonBit, 2025 | Partial | Unknown |
| Governance | 3-of-4 multisig | Limited | Centralized |
| DeFi Integrations | None | DEXs | DEXs |
| Telegram Integration | Mini App | No | No |

---

## License

This repository is licensed under the [MIT License](LICENSE).
# Awesome KTON

A curated list of resources for KTON, the liquid staking protocol on The Open Network (TON).

## Contents

- [Overview](#overview)
- [Official Resources](#official-resources)
- [Smart Contracts](#smart-contracts)
- [Using KTON](#using-kton)
- [Developer Resources](#developer-resources)
- [Wallets](#wallets)
- [Community & Social](#community--social)
- [Media Kit](#media-kit)

## Overview

**KTON** is a liquid staking protocol on TON. Stake Gram (the coin of the TON network, formerly Toncoin) and receive KTON, which earns validator rewards while it stays transferable. To get Gram back, redeem KTON through the pool.

- **Fees:** 16% of the staking rewards (the APY shown in the app is already net of it); no deposit fee. A withdrawal paid at the pool's next rotation is free; one paid at once costs 0.2%.
- **Governance:** pool settings and admin actions need 3 of 4 multisig signatures.
- **Audit:** TonBit, 2025.
- **KTON Premium (PKTON)** is a separate pool for vesting contracts.

## Official Resources

- [Website](https://kton.io/) - Official KTON website
- [dApp](https://app.kton.io/) - Stake and withdraw
- [Telegram Mini App](https://t.me/ktonio_bot) - KTON in Telegram
- [Documentation](https://docs.kton.io/) - KTON documentation
- [KTON Premium](https://premium.kton.io/) - Staking for vesting contracts
- [TON App Listing](https://ton.app/staking/kton-lst?id=4695) - KTON on TON Apps

## Smart Contracts

- **KTON pool:** [`EQA9HwEZD_tONfVz6lJS0PVKR5viEiEGyj9AuQewGQVnXPg0`](https://tonviewer.com/EQA9HwEZD_tONfVz6lJS0PVKR5viEiEGyj9AuQewGQVnXPg0)
- **KTON token (jetton master):** [`EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw`](https://tonviewer.com/EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw) ([Tonscan](https://tonscan.org/jetton/EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw))
- [Source code](https://github.com/KTON-IO/liquid-staking-contract) - Open source contracts
- [Audit Report](https://github.com/KTON-IO/liquid-staking-contract/blob/v2/KTON-Final-Audit-Report.pdf) - TonBit, 2025

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

## Using KTON

### Turning KTON back into Gram
- [Withdraw in the dApp](https://app.kton.io/) - Redeem KTON through the pool at its own rate: **Withdraw now** pays at once from the pool's idle balance for the instant-withdrawal fee (0.2% as of November 2026, shown before you sign), or wait for the next rotation and pay no fee.
- Please do not sell KTON on a DEX. DEX pools set their own price for KTON, and it has been well below the pool's rate: on 2026-11-05 selling on STON.fi paid about 6% less than redeeming.

### Market Data
- [CoinGecko](https://www.coingecko.com/en/coins/kton-staked-kton) - KTON price data
- [DeFiLlama](https://defillama.com/protocol/kton) - KTON TVL

## Developer Resources

- [KTON SDK](https://github.com/KTON-IO/KTON-SDK) - TypeScript SDK on npm as [`kton-sdk`](https://www.npmjs.com/package/kton-sdk): stake, unstake, rates and pool data for both pools
- [KTON-IO Organization](https://github.com/KTON-IO) - GitHub organization
- [KTON Documentation](https://docs.kton.io/) - Developer documentation

## Wallets

Any wallet that supports TON Connect can connect to the dApp and stake. For example:

- [Keeper](https://keeperwallet.com/) (formerly Tonkeeper) - Self-custodial wallet
- [My Wallet](https://mywallet.io/) (formerly MyTonWallet) - Self-custodial wallet
- [Tonhub](https://tonhub.com/) - Native TON mobile wallet
- [Bitget Wallet](https://web3.bitget.com/) - Multi-chain wallet with TON support
- [iMe](https://imem.app/) - Multi-chain wallet with TON support
- [Ledger](https://www.ledger.com/) - Hardware wallet with TON support

## Community & Social

- [Telegram Group](https://t.me/kton_group) - KTON community group
- [Telegram Channel](https://t.me/kton_channel) - KTON announcements
- [Twitter/X](https://x.com/kton_io) - KTON official Twitter

## Media Kit

- [KTON Media Kit](https://kton.io/media-kit/) - Logos, colours, naming and key facts
- [KTON Public Deck](https://docsend.com/v/tny7v/kton_public) - Public presentation deck

---

## License

This repository is licensed under the [MIT License](LICENSE).

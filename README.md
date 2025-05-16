# Awesome KTON: The Ultimate Resource for KTON and Liquid Staking on TON

This is an Awesome List-style webpage for KTON, the institutional-grade liquid staking protocol on The Open Network (TON). Here you'll find a comprehensive, well-structured, and up-to-date resource hub for everything related to KTON, including technical documentation, DeFi integrations, governance, security, developer resources, and community links.

---

## Overview

**KTON** is a next-generation liquid staking protocol purpose-built for the TON blockchain. Incubated by TONX and powered by the latest LST V2 smart contract architecture, KTON enables users to stake TON, receive liquid staking tokens ($KTON), and unlock liquidity without sacrificing staking rewards. KTON is designed for both retail and institutional users, offering enterprise-grade security, seamless Telegram integration, and a robust DeFi ecosystem.

---

## Why KTON?

- **Unmatched Flexibility:** Stake as little as 1 TON, with no lock-up period.
- **High Yield, High Liquidity:** Earn staking rewards while using $KTON in DeFi protocols.
- **Institutional-Grade Security:** Audited smart contracts, advanced governance, and risk controls.
- **Telegram Integration:** Easy onboarding for 950M+ Telegram users via Mini Apps.
- **DeFi Ready:** $KTON is compatible with leading TON DEXs, lending, and yield protocols.
- **First Mover:** The first public staking protocol on TON since 2022.

---

## Contents

- [Awesome KTON: The Ultimate Resource for KTON and Liquid Staking on TON](#awesome-kton-the-ultimate-resource-for-kton-and-liquid-staking-on-ton)
  - [Overview](#overview)
  - [Why KTON?](#why-kton)
  - [Contents](#contents)
  - [KTON Basics](#kton-basics)
  - [Technical Architecture](#technical-architecture)
  - [DeFi Integrations](#defi-integrations)
  - [Governance \& Tokenomics](#governance--tokenomics)
  - [Security \& Audits](#security--audits)
  - [Developer Resources](#developer-resources)
  - [Comparisons](#comparisons)
  - [Roadmap \& Future Plans](#roadmap--future-plans)
  - [Community \& Social](#community--social)
  - [Media Kit \& Branding](#media-kit--branding)

---

## KTON Basics

- **Website:** [kton.io](https://kton.io/)
- **App:** [app.kton.io](https://app.kton.io/)
- **TON Staking:** [ton.org/en/stake](https://ton.org/en/stake)
- **TON App Listing:** [ton.app/staking/kton-lst?id=4695](https://ton.app/staking/kton-lst?id=4695)
- **Whitepaper & Docs:** [github.com/KTON-IO/liquid-staking-contract](https://github.com/KTON-IO/liquid-staking-contract)
- **Medium Blog:** [medium.com/kton-io](https://medium.com/kton-io)

**What is KTON?**  
KTON is a liquid staking protocol on TON, allowing users to deposit TON and receive $KTON tokens. These tokens represent a claim on the staked assets and can be used across DeFi protocols for trading, lending, and yield strategies, all while continuing to earn staking rewards. There is no minimum lock-up, and users can start with as little as 1 TON.

---

## Technical Architecture

KTON is built on the **LST V2 (Liquid Staking Token Version 2)** framework developed by the TonCore (NEWTON) team. This architecture is modular, security-focused, and designed for both institutional and retail adoption. Key features include:

- **Separation of Roles:** Distinct smart contracts for pool management, controllers, and governance.
- **Nominator Pools:** Users deposit TON, receive $KTON, and participate in validation rewards.
- **Controller Contracts:** Interface with TON Elector for validator operations.
- **Governance Contracts:** Manage risk, fees, upgrades, and treasury.
- **Advanced Risk Management:** Emergency halter role, treasury separation, and SudoerExecutor for secure upgrades.
- **Instant Withdrawals:** Users can swap $KTON for TON with a dynamic fee for instant liquidity.
- **MEV Optimization:** Maximizes staking returns through validator efficiency.
- **Security Audited:** Comprehensive audit completed in April 2025; all critical issues addressed.

For a visual overview and technical deep dive, see the %20GitHub%5D(https%3A%2F%2Fgithub.com%2FKTON-IO%2Fliquid-staking-contract)%5Bstep-e62564%2Cartifact%2C0).

---

## DeFi Integrations

KTON is designed to be a core building block in the TON DeFi ecosystem. $KTON can be used as:

- **Collateral in Lending Protocols**
- **Liquidity on DEXs:** Trade $KTON on [STON.fi](https://app.ston.fi/swap?ft=TON&tt=EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw&chartVisible=false), [DeDust](https://dedust.io/swap/TON/EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw)
- **Yield Farming & Aggregators**
- **DeFi Apps:** Integrated with major TON DeFi protocols, and compatible with new entrants like Ethena and Curve Finance.

**On-chain Data:**  
- [TON Viewer: KTON Jetton](https://tonviewer.com/EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw)
- [TONScan: KTON Contract](https://tonscan.org/jetton/EQBuIhXNNkWf9AW9miNGNTSO_uFZ23ejfIWrieXge5f733mw)

---

## Governance & Tokenomics

KTON employs a decentralized governance model with advanced features:

- **DAO Governance:** Holders of $KTON will participate in protocol upgrades and risk management.
- **Dual-Token Model:** Future roadmap includes a governance token in addition to $KTON.
- **Treasury Management:** Dedicated smart contract for fee collection and protocol funding.
- **Role-Based Controls:** Emergency halter, sudoer (upgrade), approver, and treasury roles for robust protocol management.
- **Rewards Distribution:** Flexible profit-sharing between stakeholders, with both static and dynamic (revenue share) models.

---

## Security & Audits

**Security First:**  
- **Comprehensive Audit:** KTON V2 underwent a full audit in April 2025; no critical vulnerabilities found. All issues were addressed prior to mainnet launch.
- **Role-Based Access:** Separation of duties for critical operations (halt, upgrade, treasury).
- **Time-Delayed Upgrades:** SudoerExecutor ensures safe, auditable contract upgrades.
- **Circuit Breakers:** Halter can pause deposits and withdrawals in emergencies.
- **Enhanced Error Handling:** Safer message handling, descriptive error codes, and improved test coverage.

**Key Audit Highlights:**  
- No critical vulnerabilities
- Enhanced role restrictions
- Strong validation and error handling
- Modular and upgradable contract design

---

## Developer Resources

- **GitHub (Protocol & Contracts):** [KTON-IO/liquid-staking-contract](https://github.com/KTON-IO/liquid-staking-contract)
- **Organization:** [KTON-IO](https://github.com/KTON-IO)
- **API & SDK:** See [TONX API](https://tonx.ai/) for RPC and developer tools used by KTON and other TON dApps.
- **Telegram Mini App:** [@ktonio_bot](https://t.me/ktonio_bot) for instant staking and DeFi access in Telegram.
- **Community Support:** [KTON Group Telegram](https://t.me/kton_group)

---

## Comparisons

**KTON vs. Other TON Liquid Staking Protocols**

| Feature                | KTON          | Tonstakers      | TON Whales    |
|------------------------|---------------|-----------------|---------------|
| **Architecture**       | LST V2 (modular, institutional-grade) | LST V1 | Pool-based |
| **Minimum Stake**      | 1 TON         | 1 TON           | 50 TON        |
| **Instant Withdrawals**| Yes           | Yes             | Yes           |
| **Security Audit**     | 2025, full audit | Partial        | Unknown       |
| **Governance**         | DAO, dual-token roadmap | Limited      | Centralized   |
| **DeFi Integrations**  | DEXs, lending, yield | DEXs         | DEXs          |
| **Telegram Integration**| Mini App      | No              | No            |
| **First Mover**        | Yes (since 2022) | No             | No            |

KTON sets the standard for modular, upgradable, and security-focused liquid staking on TON, with extensive DeFi and Telegram integrations.

---

## Roadmap & Future Plans

- **2025:**
  - Launch of DAO governance and dual-token model
  - Vesting contract support for institutional clients and OTC deals
  - Further DeFi integrations (e.g., with Curve Finance, Ethena)
  - Expansion into US and global markets
  - Ongoing upgrades to LST V2 architecture and security enhancements
- **Beyond:**
  - Continued focus on security, composability, and institutional adoption
  - New staking strategies and flexible pool management

---

## Community & Social

- **Telegram Group:** [@kton_group](https://t.me/kton_group)
- **Telegram Mini App:** [@ktonio_bot](https://t.me/ktonio_bot)
- **Telegram Channel:** [@kton_channel](https://t.me/kton_channel)
- **Twitter/X:** [@kton_io](https://x.com/kton_io)
- **TONX (Incubator):** [tonx.ai](https://tonx.ai/)

---

## Media Kit & Branding

- **Logos & Symbols:** See %5D(https%3A%2F%2Fwww.notion.so%2F1a1811267273809b8145e1d4d457db77)%20for%20official%20SVG%2FPNG%20assets%2C%20color%20palettes%2C%20and%20usage%20guidelines%5Bstep-dc5e76%2Cartifact%2C0).
- **Wordmarks:** Available in multiple formats for use in presentations, websites, and integrations.


---

**Awesome KTON** aims to be the go-to resource for users, developers, and institutions seeking to maximize the potential of liquid staking on TON. For the latest updates, follow the official channels and contribute to the growing KTON ecosystem!
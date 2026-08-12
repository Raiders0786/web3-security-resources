---
title: SOC and Monitoring
description: SOC and Monitoring page in the Web3 Security Resources 2026 hub.
---

# SOC and Monitoring

Protocol monitoring should cover contracts, privileged actions, frontend drift,
DNS, dependencies, wallets, APIs, and governance.

## Monitoring Resources

| Resource | Tier | Use |
| --- | --- | --- |
| [Forta](https://forta.org/) | Use in real audits | On-chain detection bots and alerting. |
| [OpenZeppelin Defender Monitor](https://docs.openzeppelin.com/defender) | Use in real audits | Contract event and admin monitoring. |
| [Hypernative](https://www.hypernative.io/) | Paid / certification | Real-time exploit and anomaly detection. |
| [Tenderly Alerts](https://tenderly.co/) | Use in real audits | Transaction and contract monitoring. |
| [Dune](https://dune.com/) | Situational / advanced | Custom dashboards and queries. |
| [EigenPhi](https://eigenphi.io/) | Situational / advanced | MEV and transaction behavior analysis. |
| [DigiBastion Threat Intel](https://www.digibastion.com/threat-intel) | Use in real audits | Free Web3, DeFi, supply-chain, and operational-security feed with daily, weekly, or immediate alert subscriptions. |
| [zeroShadow](https://www.zeroshadow.io/) | Paid / certification | Web3 incident response, investigations, threat intelligence, and vSOC. |
| [TRM Labs](https://www.trmlabs.com/) | Paid / certification | Wallet risk monitoring, investigations, and blockchain intelligence. |
| [VANTAGE by DigiBastion](https://vantage.digibastion.com/) | Watchlist | Maintainer-labeled domain, DNS, frontend, phishing, and Web3 trust-risk monitoring. |
| [OpenChainBench](https://openchainbench.com) | Watchlist | Free, open-source RPC reliability benchmarks, oracle deviation tracking (Chainlink/Pyth/Redstone), and MEV-protection RPC measurements. Infrastructure due diligence for protocol security engineers. MIT licensed, 20+ chains. Last verified: August 2026. |

## Alert Categories

- privileged role changes
- proxy upgrades and implementation changes
- pause/unpause and emergency action calls
- oracle deviation and stale feeds
- TVL and reserve anomalies
- bridge mint/burn mismatches
- abnormal approvals, drains, or token movements
- frontend asset hash drift
- DNS, TLS, registrar, and nameserver changes
- governance proposal creation and execution

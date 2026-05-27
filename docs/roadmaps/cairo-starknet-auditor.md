---
title: Cairo/Starknet Auditor
description: Cairo/Starknet Auditor page in the Web3 Security Resources 2026 hub.
---

# Cairo/Starknet Auditor

Audience: auditors and engineers reviewing Cairo contracts, Starknet protocols,
account abstraction, bridges, and L2 messaging.

## Outcomes

- Understand Cairo syntax, storage, components, traits, felt/arithmetic behavior, and Starknet accounts.
- Review account abstraction, signature validation, nonce handling, and transaction flows.
- Analyze L1/L2 messaging, bridge assumptions, and sequencer/finality risks.

## Roadmap

| Stage | Focus | Proof of work |
| --- | --- | --- |
| Cairo language | Types, storage, components, traits, testing | Build and test a small token or vault. |
| Starknet model | Accounts, contracts, classes, deployment, fee model | Explain account abstraction trust boundaries. |
| Security review | Access control, arithmetic, signatures, upgradeability | Write a report for a toy Cairo protocol. |
| Messaging | L1/L2 messages, replay, finality, bridge accounting | Threat model a bridge deposit/withdraw flow. |
| Advanced | Provers, DA, sequencer, appchain assumptions | Document protocol-specific assumptions. |

## Must Learn

| Resource | Why |
| --- | --- |
| [Cairo Book](https://book.cairo-lang.org/) | Primary Cairo language reference. |
| [Rareskills Cairo Tutorials](https://rareskills.io/cairo-tutorial) | Developer-friendly series for  experienced programmers. |
| [Starknet Docs](https://docs.starknet.io/) | Platform, accounts, contracts, and tooling reference. |
| [Starknet Foundry](https://foundry-rs.github.io/starknet-foundry/) | Testing framework for Cairo contracts. |
| [OpenZeppelin Cairo Contracts](https://docs.openzeppelin.com/contracts-cairo/) | Security-reviewed Cairo components and patterns. |
| [Awesome Starknet Security](https://github.com/amanusk/awesome-starknet-security) | Curated Cairo/Starknet security tools, audits, CTFs, and practice material. |

## Review Checklist

- Signature validation, nonces, and account abstraction paths are explicit.
- Storage layout and upgrade behavior are documented.
- Arithmetic assumptions are verified for field behavior and conversions.
- L1/L2 message handlers validate caller, payload, replay protection, and finality assumptions.
- Admin functions and emergency controls have clear governance and monitoring.

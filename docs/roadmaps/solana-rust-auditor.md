---
title: Rust/Solana Auditor
description: Rust/Solana Auditor page in the Web3 Security Resources 2026 hub.
---

# Rust/Solana Auditor

Audience: auditors and Rust engineers reviewing Solana programs, Anchor
applications, SPL integrations, and Token-2022 extensions.

## Outcomes

- Reason about accounts, ownership, signers, executable accounts, rent, PDAs, and CPIs.
- Review Anchor constraints without assuming they encode the full security model.
- Identify confused-deputy, arbitrary CPI, account substitution, PDA seed, and token-account bugs.
- Write tests that prove an attacker can supply malicious accounts or bypass invariants.

## Roadmap

| Stage | Focus | Proof of work |
| --- | --- | --- |
| Rust basics | Ownership, lifetimes, error handling, serialization | Read and modify a small Anchor program. |
| Solana model | Accounts, instructions, PDAs, signers, rent, sysvars | Diagram an instruction's trusted and untrusted accounts. |
| Anchor security | Constraints, account validation, IDL, CPI helpers | Break a toy program by replacing one unchecked account. |
| Token systems | SPL Token, Token-2022, ATAs, delegates, authorities | Review token transfer and authority assumptions. |
| Production review | Upgrade authority, governance, oracles, bridges, monitoring | Produce a checklist-driven audit report. |

## Must Learn

| Resource | Why |
| --- | --- |
| [Solana Docs](https://solana.com/docs) | Current platform and account-model reference. |
| [Rareskills Solana Tutorial](https://rareskills.io/solana-tutorial) | Learn Solana coming from EVM. |
| [Anchor Book](https://www.anchor-lang.com/docs) | Primary framework documentation for modern Solana programs. |
| [SPL Token Docs](https://spl.solana.com/token) | Token authority and account model reference. |
| [Token-2022 Docs](https://spl.solana.com/token-2022) | Extension model and newer token risk surface. |
| [Solana Program Security Course](https://solana.com/developers/courses/program-security) | Hands-on vulnerability examples and mitigations. |

## Use in Real Audits

| Resource | Why |
| --- | --- |
| [Solana Explorer](https://explorer.solana.com/) | Inspect programs, accounts, and transactions. |
| [Solscan](https://solscan.io/) | Practical transaction and account inspection. |
| [OtterSec Blog](https://osec.io/blog/) | Solana and low-level security research. |
| [Zellic Blog](https://www.zellic.io/blog/) | Frequent Solana, ZK, and protocol security writeups. |
| [Neodyme Solana Articles](https://neodyme.io/en/blog/) | Classic Solana bug classes and account validation pitfalls. |

## Review Checklist

- Every account has explicit owner, signer, mutability, address, and relationship checks.
- PDA seeds include domain separation and cannot be attacker-chosen in unsafe ways.
- Token accounts are tied to expected mint, authority, owner, and program.
- CPI targets are fixed or validated; attacker-supplied programs are not trusted.
- Upgrade authority, admin paths, and emergency controls are documented and monitored.

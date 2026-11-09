---
title: Incident Response
description: Incident Response page in the Web3 Security Resources 2026 hub.
---

# Incident Response

## Must Learn

| Resource | Tier | Use |
| --- | --- | --- |
| [SEAL 911](https://securityalliance.org/seal-911) | Must learn | Emergency response path for active crypto incidents. |
| [SEAL Frameworks](https://frameworks.securityalliance.org/) | Must learn | Incident readiness and operational security frameworks. |
| [Immunefi Responsible Publication Policy](https://immunefi.com/responsible-publication/) | Use in real audits | Disclosure expectations and publication rules. |
| [OpenZeppelin Defender](https://docs.openzeppelin.com/defender) | Use in real audits | Emergency admin operations and monitoring. |
| [Forta](https://forta.org/) | Use in real audits | On-chain detection bots. |
| [zeroShadow](https://www.zeroshadow.io/) | Paid / certification | Web3 incident response, investigations, threat intelligence, and vSOC. |
| [DigiBastion Threat Intel](https://www.digibastion.com/threat-intel) | Use in real audits | Free alert feed for Web3 incidents, DeFi exploits, supply-chain threats, and operational-security updates. |
| [DigiBastion Threat Intel Subscribe](https://www.digibastion.com/threat-intel?tab=subscribe) | Use in real audits | Daily, weekly, or immediate email alerts for security engineers, founders, and developers. |
| [compromised-wallet-sweeper-rescue](https://github.com/mevdao-org/compromised-wallet-sweeper-rescue) | Situational / advanced | Open-source (MIT) TypeScript scripts for moving tokens or claiming airdrops out of a compromised EOA that a sweeper bot is watching, using a sponsored Flashbots bundle; includes an EIP-7702 delegation check. |

## Minimum IR Runbook

- Severity definitions and escalation contacts.
- Wallet, multisig, governance, frontend, DNS, hosting, and comms owners.
- Pause, rate-limit, disable, or upgrade actions and their exact signers.
- Evidence preservation: tx hashes, logs, builds, DNS history, CI runs, wallet actions.
- Private triage channel and public communication template.
- External contacts: exchanges, bridges, stablecoin issuers, RPC providers, hosting, registrar, SEAL 911.

## Drills

Run tabletop exercises for:

- oracle manipulation
- private key compromise
- frontend wallet-drainer injection
- bridge accounting mismatch
- governance takeover
- dependency compromise
- DNS or registrar takeover

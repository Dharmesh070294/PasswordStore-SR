# PasswordStore — Security Review Portfolio Project

## Overview
PasswordStore is a compact smart contract security lab focused on access control, sensitive data exposure, and basic report writing. This repository is presented as a portfolio project to demonstrate audit scoping, vulnerability analysis, and secure coding review.

## Why This Project Matters
Although intentionally simple, PasswordStore is ideal for showing foundational security thinking:
- Access control validation
- Misconceptions about on-chain privacy
- State visibility and data exposure
- Basic audit methodology and reporting

## Objectives
- Understand the protocol design and trust assumptions
- Review privilege boundaries and write paths
- Identify sensitive data exposure risks
- Document findings in a professional audit format

## Scope
Core areas reviewed:
- Password storage logic
- Authorization checks
- Read/write access patterns
- Visibility assumptions

## Security Themes
- Broken or missing access control
- False privacy assumptions on public blockchains
- Insecure storage of sensitive information
- Missing event coverage and operational transparency

## What This Repository Shows
- Structured audit notes
- Vulnerability writeups
- Root-cause analysis
- Remediation recommendations
- Optional proof-of-concept tests

## Suggested Repository Structure
```text
PasswordStore/
├── README.md
├── findings/
│   ├── H-01-access-control.md
│   └── M-01-sensitive-data-exposure.md
├── notes/
│   └── scoping-notes.md
├── poc/
│   └── passwordstore.t.sol
└── report/
    └── audit-report.md
```

## Key Learning Outcomes
- Public blockchain data is not private
- Small contracts can still contain critical flaws
- Good reporting matters as much as bug discovery
- Scope understanding drives faster auditing

## Run Locally
```bash
forge install
forge build
forge test
```

## Portfolio Value
This project demonstrates foundational audit skills: understanding trust boundaries, spotting security assumptions, and communicating findings clearly.

## Disclaimer
This repository is for educational, research, and portfolio purposes only.

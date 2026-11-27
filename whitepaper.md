# Chitos Coin Whitepaper
Version 0.1 | Pre-launch draft

## Executive summary
Chitos Coin (CHTC) is a proposed community-oriented BEP-20 token combining meme culture with a planned AI utility ecosystem. The project is in pre-launch development. The token itself does not provide AI services, ownership, dividends or guaranteed returns.

## Vision and proposed utility
The proposed ecosystem explores AI-assisted content creation, productivity tools and community participation. Potential future uses include access credits, service payments and contribution rewards, subject to technical feasibility, legal review and actual product delivery. No AI product or redemption mechanism is currently operational.

## Token architecture
The planned BNB Smart Chain mainnet token uses an OpenZeppelin-based ERC-20 implementation with 18 decimals, a one-time initial mint of 1,000,000,000 CHTC, holder-authorized burning and EIP-2612 permit. The reviewed design has no additional mint function, transfer tax, privileged owner controls or upgrade mechanism. Burning reduces total supply; permit signatures can authorize spending and must be handled carefully.

## Distribution and vesting
The proposed launch distribution unlocks 50 million CHTC (5%) and allocates 950 million (95%) to six separate vesting contracts. No presale is planned. Each period is 30 days, not a calendar month. Unlocks accrue in discrete monthly increments after the cliff; the first increment is one month after cliff end. Anyone may call release, but funds go only to the immutable beneficiary. Release is not automatic and requires full remaining funding. There is no administrative rescue or beneficiary replacement. Liquidity allocation vesting is not a liquidity-pool token lock.

## Custody and transparency
Six separate 2-of-3 Safe multisig beneficiaries are planned, using the same three signers. Current signer storage on one computer creates correlated compromise risk; independent devices or hardware wallets are recommended before production custody. Mainnet addresses, funding transactions and verified source links will be published only after deployment and verification.

## Development status and security
Reported testnet checks passed 164/164, including allocation reconciliation, early-release rejection and vesting boundary calculations. A two-owner Safe execution and single-signature rejection were tested. Actual post-unlock release, third-signer execution and remaining security review are incomplete. No independent audit has been completed. Mainnet deployment and public trading have not occurred.

## Roadmap
Phase 1: token design, implementation and testnet validation (substantially completed, with open security items). Phase 2: complete security and legal review, deploy and verify mainnet contracts, publish addresses. Phase 3: launch website and evaluate liquidity provision and decentralized trading. Phase 4: develop and validate AI utility, community and transparent reporting. Phase 5: evaluate exchange applications, including Binance Global, subject to eligibility and independent approval. No listing is guaranteed.

## Risks and legal notice
CHTC is experimental. Smart contract defects, permanent loss of keys, irreversible transfers, market volatility, illiquidity, regulatory changes and failure to deliver utility may cause total loss. This document is informational, not an offer, investment recommendation or promise of returns. Before public distribution, marketing or trading, obtain jurisdiction-specific legal advice, including Thai digital-asset requirements. No exchange affiliation or endorsement is claimed.

## Governance and updates
Project decisions are initially coordinated by the project team; token voting is not implemented. Proposed allocations and roadmap may be revised before mainnet deployment. After deployment, immutable contract parameters cannot be changed. Publish material changes, contract addresses, custody arrangements and known risks with versioned updates.

| Allocation | Total M | Day 0 M | Locked M | Cliff | Release |
|---|---:|---:|---:|---:|---:|
| Community & Rewards | 400 | 10 | 390 | 0 | 48 |
| Liquidity & Exchange | 200 | 30 | 170 | 0 | 36 |
| AI Utility Ecosystem | 150 | 5 | 145 | 0 | 48 |
| Founder & Team | 100 | 0 | 100 | 12 | 36 |
| Marketing & Partnership | 100 | 5 | 95 | 0 | 36 |
| Reserve | 50 | 0 | 50 | 24 | 24 |
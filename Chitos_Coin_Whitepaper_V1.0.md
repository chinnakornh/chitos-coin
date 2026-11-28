# Chitos Coin Mainnet Whitepaper V1.0

## CHTC / WHITEPAPER

## Community culture. AI ambition.

Version 1.0 | Mainnet edition | 28 November 2026

BNB Smart Chain | Chain ID 56 | BEP-20

| Initial supply | Initial vesting | Initial multisig |
| --- | --- | --- |
| 1 billion CHTC | 950 million (95%) | 50 million (5%) |

Mainnet deployment and initial distribution are reported complete. Public trading has not launched. AI Hub is in private beta. No independent security audit has been completed. This document is informational, not an investment offer.

[Official project website](https://chinnakornh.github.io/chitos-coin/)

## 01 / Executive summary

Chitos Coin (CHTC) is a community-oriented BEP-20 token combining meme culture with a planned AI utility ecosystem. The token is deployed on BNB Smart Chain mainnet. Its design emphasizes a fixed initial issuance, scheduled distribution and transparent custody. The token itself does not provide AI services, equity, ownership rights, dividends or guaranteed returns.

## 02 / Vision and proposed utility

The ecosystem explores AI-assisted content creation, productivity tools and community participation. CHITOS AI HUB is available in private beta with five AI tools and wallet connection. No token purchase is required. Token payments, redemption, wallet-based authentication and production credit accounting are not enabled.

Potential future uses include access credits, service payments and contribution rewards, subject to technical feasibility, legal review and actual product delivery. The beta is not a production-grade financial service; authentication, abuse controls and operational security require further development.

[CHITOS AI HUB](https://chinnakornh.github.io/chitos-coin/ai/)

## 03 / Token architecture

| Parameter | Mainnet configuration |
| --- | --- |
| Name / symbol | Chitos Coin / CHTC |
| Network / decimals | BNB Smart Chain (56) / 18 |
| Initial issuance | 1,000,000,000 CHTC; one-time mint |
| Implementation | OpenZeppelin 5.6.0; ERC20, Burnable, Permit |
| Compiler | Solidity 0.8.34; optimizer 200; Cancun |
| Controls | No additional mint, transfer tax, owner controls or upgrade mechanism |

Holder-authorized burning reduces total supply. EIP-2612 permit authorizes allowances by signature; users must verify spender, amount, deadline and domain before signing.

[0x5ab5c557c2eb29fc1c3642b31345049f0dc31208](https://bscscan.com/address/0x5ab5c557c2eb29fc1c3642b31345049f0dc31208#code)

## 04 / Distribution and vesting

At initial distribution completion, 950 million CHTC were allocated to six funded vesting contracts and 50 million CHTC to four of six Safe wallets. The deployer held zero CHTC at that snapshot. No presale is planned. Initial allocation is not equivalent to circulating supply.

| Allocation | Total M | Initial M | Vesting M | Cliff | Release |
| --- | --- | --- | --- | --- | --- |
| Community & Rewards | 400 | 10 | 390 | 0 | 48 |
| Liquidity & Exchange | 200 | 30 | 170 | 0 | 36 |
| AI Utility Ecosystem | 150 | 5 | 145 | 0 | 48 |
| Founder & Team | 100 | 0 | 100 | 12 | 36 |
| Marketing & Partnership | 100 | 5 | 95 | 0 | 36 |
| Reserve | 50 | 0 | 50 | 24 | 24 |
| Total | 1000 | 50 | 950 | - | - |

M = million CHTC. Each period is exactly 30 days. The common start is 29 November 2026, 13:30:12 UTC+7 (Unix 1795933812). First release eligibility occurs one period after cliff end. Anyone may call release; tokens go only to the immutable beneficiary. Release is not automatic and requires full remaining funding. There is no administrative rescue or beneficiary replacement. Liquidity allocation vesting is not an LP token lock.

| Allocation | First eligible release | Final scheduled vesting |
| --- | --- | --- |
| Community & Rewards | 29 Dec 2026 | 08 Nov 2030 |
| Liquidity & Exchange | 29 Dec 2026 | 13 Nov 2029 |
| AI Utility Ecosystem | 29 Dec 2026 | 08 Nov 2030 |
| Founder & Team | 24 Dec 2027 | 08 Nov 2030 |
| Marketing & Partnership | 29 Dec 2026 | 13 Nov 2029 |
| Reserve | 18 Dec 2028 | 08 Nov 2030 |

All dates use 13:30:12 UTC+7. Scheduled vested amount is allocation multiplied by completed release periods divided by release duration, rounded down in base units and capped at allocation. Actual transfers require an on-chain release transaction.

## 05 / Custody and transparency

Six separate Safe 1.4.1 wallets are configured with a 2-of-3 threshold and the same three signers. Shared computer storage creates correlated compromise risk. Independent devices or hardware wallets, offline backups and periodic custody review are recommended before further asset movements.

The project dashboard displays the historical initial distribution snapshot and contractual schedule, not real-time balances or circulating supply. Explorer links below allow readers to inspect each contract.

[Official transparency dashboard](https://chinnakornh.github.io/chitos-coin/)

[Distribution completion reference block 136205293](https://bscscan.com/block/136205293)

Mainnet registry: each vesting contract pays its corresponding Safe. The addresses below are public contract addresses, not payment instructions.

**Community & Rewards**

[Vesting: 0x18a545f86eeab144f7eca2627e1582dee1ab7332](https://bscscan.com/address/0x18a545f86eeab144f7eca2627e1582dee1ab7332)

[Safe: 0x342769262473f589bef2550b000c0615aef9899b](https://bscscan.com/address/0x342769262473f589bef2550b000c0615aef9899b)

**Liquidity & Exchange**

[Vesting: 0xf706229c1c918284cc453b9cbcfa15d3da1bcac8](https://bscscan.com/address/0xf706229c1c918284cc453b9cbcfa15d3da1bcac8)

[Safe: 0x41c889c86e3030c112cf21d9ecb3846166fe094f](https://bscscan.com/address/0x41c889c86e3030c112cf21d9ecb3846166fe094f)

**AI Utility Ecosystem**

[Vesting: 0x7d7722fdaeb8a806530f07a171a3d1bb0f72a4c6](https://bscscan.com/address/0x7d7722fdaeb8a806530f07a171a3d1bb0f72a4c6)

[Safe: 0x090fdb6202def8f5484f07b53f2b9451379374e4](https://bscscan.com/address/0x090fdb6202def8f5484f07b53f2b9451379374e4)

**Founder & Team**

[Vesting: 0xd1c3bd4a35826211079e0cd26ee59e4f0ac754e8](https://bscscan.com/address/0xd1c3bd4a35826211079e0cd26ee59e4f0ac754e8)

[Safe: 0xd50a0d26ca7986b6b5f7f6e0141cd1b99b3fbbd8](https://bscscan.com/address/0xd50a0d26ca7986b6b5f7f6e0141cd1b99b3fbbd8)

**Marketing & Partnership**

[Vesting: 0x7338da945bd6c53c969ee34cc96d34c10da5252a](https://bscscan.com/address/0x7338da945bd6c53c969ee34cc96d34c10da5252a)

[Safe: 0x6c37df37d76fc9bc5540e53a500036c9fb3d08e8](https://bscscan.com/address/0x6c37df37d76fc9bc5540e53a500036c9fb3d08e8)

**Reserve**

[Vesting: 0x29efb18f38eb679d0bc81d0771e11259531c0545](https://bscscan.com/address/0x29efb18f38eb679d0bc81d0771e11259531c0545)

[Safe: 0xcc5eeb395e4710dccb66cb7db327b919d672dd20](https://bscscan.com/address/0xcc5eeb395e4710dccb66cb7db327b919d672dd20)

## 06 / Development status and security

Project records report 13 deployed contracts: one token, six vesting contracts and six Safe proxies. All six vesting contracts were funded at initial distribution completion. BscScan confirmed matching bytecode and ABI for the token and Community vesting contract. Other vesting contracts display similar-match source information; separate explorer verification and proxy linking are not complete for every contract. Source verification is not a security audit.

Reported testnet checks passed 164/164, including allocation reconciliation, early-release rejection and vesting boundary calculations. A two-owner Safe execution and single-signature rejection were tested. Actual post-unlock release, third-signer execution and remaining security review are incomplete. Mainnet deployment and distribution checks were performed using project scripts; no independent audit has been completed.

[Token deployment transaction](https://bscscan.com/tx/0xd0a1db0f2353a40e3d701e863f0f2f9e46532042687bfaa8b3d0a0ffadb49179)

[Safe singleton 1.4.1](https://bscscan.com/address/0x41675C099F32341bf84BFc5382aF534df5C7461a)

## 07 / Roadmap

| Phase | Status / scope |
| --- | --- |
| 1. Foundation | Substantially completed; open security items remain. |
| 2. Mainnet | Deployment and initial distribution reported complete; additional explorer checks and legal review remain. |
| 3. Market readiness | Evaluate DEX liquidity, legal requirements and custody readiness before public trading. |
| 4. Ecosystem | Validate AI utility, improve beta controls, build community and transparent reporting. |
| 5. Exchange applications | Evaluate eligibility for Binance Global and other exchanges; independent approval required. No listing guaranteed. |

## 08 / Risks and legal notice

CHTC is experimental. Smart contract defects, permanent loss or compromise of keys, irreversible transfers, market volatility, illiquidity, regulatory changes and failure to deliver utility may cause total loss. Vesting cannot guarantee market stability or liquidity. Multisig custody does not eliminate signer compromise or collusion. AI services may produce inaccurate content, experience outages or change availability.

This document is informational, not an offer, investment recommendation or promise of returns. Before public distribution, marketing or trading, obtain jurisdiction-specific legal advice, including Thai digital-asset requirements. No exchange affiliation, endorsement or approval is claimed. No public trading has launched as of this edition.

## 09 / Governance and updates

Project decisions are initially coordinated by the project team; token voting is not implemented. Immutable token and vesting parameters cannot be changed after deployment. Safe owners and thresholds can be changed through authorized Safe transactions. Future utility and roadmap plans may change. Material changes, custody arrangements and known risks should be published with versioned updates.

## Official channels and document record

[Website](https://chinnakornh.github.io/chitos-coin/)

[GitHub](https://github.com/chinnakornh/chitos-coin)

[X](https://x.com/ChitosCoinAI)

[Telegram](https://t.me/ChitosCoinAI)

[Discord](https://discord.gg/GyaH9vCHdU)

Revision basis: Whitepaper v0.1 (27 November 2026), project deployment manifest and reported completion snapshot, BscScan screenshots and dashboard screenshots supplied by the project operator. This edition does not constitute an independent live-chain attestation.

Never send funds or disclose wallet credentials to anyone claiming to represent CHTC.

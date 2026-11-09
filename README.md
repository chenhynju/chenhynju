# Hi, I'm Chen — Smart Contract & Protocol Engineer

I build DeFi primitives, account-abstraction infrastructure and chain data pipelines with an
evidence-first workflow: every project below ships executable tests, fuzz/invariant campaigns,
an AI-assisted security & economic self-assessment, and — where deployed — Sourcify-verified
testnet contracts with machine-checkable receipts.

## Web3 Portfolio (5 production-grade projects)

| Project | What it demonstrates | Evidence |
| --- | --- | --- |
| [D01 · Constant-Product AMM](https://github.com/chenhynju/d01-amm-dex) | Factory/pair/router from scratch, permit LP token, flash swaps, cumulative prices, fee-adjusted invariant fuzzing | 43 contract tests + invariant suites · Sourcify exact-match on Base Sepolia |
| [D02 · Isolated Lending](https://github.com/chenhynju/b2-lending) | Collateralized vault with indexed debt, LTV/liquidation math, atomic bad-debt socialization, oracle boundaries | 66 contract tests (unit/fuzz/invariant/differential) · live verified demo market on Base Sepolia |
| [W05 · Smart Account Platform](https://github.com/chenhynju/w05-smart-account-platform) | ERC-4337 v0.8 accounts: CREATE2 factory, threshold owners, scoped session keys, WebAuthn/P256, delayed guardian recovery, local bundler | 41 contract + 11 TS tests · full local UserOperation lifecycle |
| [W07 · Chain Observatory](https://github.com/chenhynju/w07-chain-observatory) | Block-addressable Uniswap V2 analytics indexer (Ponder): reserves, volume, fees, holders, explicit coverage & finality model, reorg recovery | 14 TS + 8 fixture tests · dual-testnet fixture indexing with verified receipts |
| [D11 · RWA Tokenization Platform](https://github.com/chenhynju/d11-rwa-tokenization-platform) | Permissioned bond-unit lifecycle: identity registry, jurisdiction policy, holding limits, dual-party issuance, reserved redemption with receipt reconciliation | 48 contract tests · three-role on-chain acceptance on Base Sepolia (Sourcify exact-match, 7 contracts) |

Every repository documents its evidence boundary honestly: PASS/FAIL/BLOCKED/NOT_RUN gates,
frozen commit hashes for reviews, and no fabricated metrics. Security reports are labeled
AI-Assisted Self-Assessment — not claimed as independent audits.

## How I work

`Requirement → Design → Code → Test (unit/fuzz/invariant/fork/differential) → Economic security → Self-audit with PoC → Testnet deploy → Verify → Document`

- **Solidity / Foundry** — pinned toolchains, vendored dependencies, reproducible builds
- **Protocol economics** — invariant definitions, attack-scenario modeling, independent reference implementations (no JS floats as truth)
- **TypeScript / Next.js / viem / wagmi / Ponder** — wallet UIs and indexers that meet the contracts, not mock screenshots
- **Docs that survive interviews** — ADRs, code walkthroughs, and "why" recorded per module

## Beyond Web3

Full-stack products in production: multi-tenant SaaS collaboration (NestJS/Next.js/Postgres RLS),
high-concurrency e-commerce (Next.js/Redis/BullMQ), and my bilingual personal site with a custom
CMS, AI tooling and payment integration.

---

📫 Reach me via the contact form on my site, or open an issue in any portfolio repository.

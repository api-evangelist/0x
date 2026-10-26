# 0x

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

0x is the institutional-grade DEX aggregation and crypto liquidity infrastructure platform that powers token swaps inside hundreds of consumer wallets, exchanges, and onchain apps (Coinbase, MetaMask, Phantom, Brave, Rainbow, Matcha, and more). The 0x API surface aggregates 150+ liquidity sources — public AMMs and exclusive professional market makers — across 20+ EVM chains, with cross-chain reach into Solana, HyperCore, and Tron via 16+ bridge providers. Settlement runs through the Permit2-based 0x Settler contracts, and integrators get a unified API key, a TypeScript SDK, an official Agent Skill, and a hosted MCP server for AI-assisted development.

- **Website:** [https://0x.org](https://0x.org)
- **Documentation:** [https://docs.0x.org](https://docs.0x.org)
- **Dashboard / Sign Up:** [https://dashboard.0x.org/create-account](https://dashboard.0x.org/create-account)
- **Pricing:** [https://0x.org/pricing](https://0x.org/pricing)
- **GitHub:** [https://github.com/0xProject](https://github.com/0xProject)
- **Status:** [https://status.0x.org](https://status.0x.org)

## APIs

### 0x Swap API
Institutional-grade DEX aggregation returning indicative prices, firm quotes, and ready-to-sign transaction calldata for token swaps across 150+ liquidity sources on 20+ EVM chains. Two allowance flows: AllowanceHolder (recommended, multisig-friendly) and Permit2 (gas-optimised with EIP-712).

- **Base URL:** `https://api.0x.org`
- **Authentication:** API key header `0x-api-key` + version header `0x-version: v2`
- **OpenAPI:** [openapi/0x-api.yaml](openapi/0x-api.yaml)
- **Documentation:** [https://docs.0x.org/0x-swap-api/introduction](https://docs.0x.org/0x-swap-api/introduction)

### 0x Gasless API
Lets end users swap tokens without holding the native gas asset (ETH, BNB, AVAX, etc.). The taker signs Permit2 + meta-transaction EIP-712 payloads off-chain; 0x relayers submit on-chain. Gas fees are deducted from the sell token.

- **Base URL:** `https://api.0x.org`
- **Authentication:** API key header `0x-api-key` + version header `0x-version: v2`
- **OpenAPI:** [openapi/0x-api.yaml](openapi/0x-api.yaml)
- **Documentation:** [https://docs.0x.org/gasless-api/introduction](https://docs.0x.org/gasless-api/introduction)

### 0x Cross-Chain API (Private Beta)
Any-token, any-chain bridging API aggregating 16+ bridge providers (Across V4, Relay, Bungee, CCIP, Squid Coral, NEAR Intents, OFT, Mayan, Circle CCTP, Arbitrum / Linea / Superchain canonical bridges, HyperCore). Includes streaming quote updates and reaches Solana, HyperCore, and Tron.

- **Base URL:** `https://api.0x.org`
- **Authentication:** API key header `0x-api-key`
- **OpenAPI:** [openapi/0x-cross-chain.yaml](openapi/0x-cross-chain.yaml)
- **Documentation:** [https://docs.0x.org/cross-chain-api/introduction](https://docs.0x.org/cross-chain-api/introduction)

### 0x Trade Analytics API
Read-only API for retrieving the integrator's historical swap and gasless trade records with surplus, integrator fee accrual, taker, route, and per-trade settlement detail. Used for monetisation reporting and accounting reconciliation.

- **Base URL:** `https://api.0x.org`
- **OpenAPI:** [openapi/0x-api.yaml](openapi/0x-api.yaml)

### 0x Sources API
Returns the active aggregated liquidity sources (AMMs, RFQ market makers, private liquidity venues) currently routed against by the Swap and Gasless engines on a given chain.

- **Base URL:** `https://api.0x.org`
- **OpenAPI:** [openapi/0x-api.yaml](openapi/0x-api.yaml)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [openapi/0x-api.yaml](openapi/0x-api.yaml) | 0x API v2 — Swap, Gasless, Sources, Trade Analytics (14 operations) |
| [openapi/0x-cross-chain.yaml](openapi/0x-cross-chain.yaml) | 0x Cross-Chain API v1 — quotes, status, sources, history, streaming (5 operations) |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [json-schema/0x-swap-quote-schema.json](json-schema/0x-swap-quote-schema.json) | Firm swap quote with calldata |
| [json-schema/0x-swap-price-schema.json](json-schema/0x-swap-price-schema.json) | Indicative swap price |
| [json-schema/0x-gasless-trade-schema.json](json-schema/0x-gasless-trade-schema.json) | Gasless trade payload + approval |
| [json-schema/0x-gasless-trade-status-schema.json](json-schema/0x-gasless-trade-status-schema.json) | Gasless trade lifecycle status |
| [json-schema/0x-cross-chain-quote-schema.json](json-schema/0x-cross-chain-quote-schema.json) | Cross-chain bridge quote |
| [json-schema/0x-supported-chain-schema.json](json-schema/0x-supported-chain-schema.json) | Supported chain descriptor |
| [json-schema/0x-liquidity-source-schema.json](json-schema/0x-liquidity-source-schema.json) | Liquidity source descriptor |
| [json-schema/0x-trade-analytics-record-schema.json](json-schema/0x-trade-analytics-record-schema.json) | Single trade record (analytics) |
| [json-schema/0x-error-schema.json](json-schema/0x-error-schema.json) | Canonical 0x error envelope |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [json-structure/0x-swap-quote-structure.json](json-structure/0x-swap-quote-structure.json) | Field-level docs for the firm swap quote |
| [json-structure/0x-gasless-trade-structure.json](json-structure/0x-gasless-trade-structure.json) | Field-level docs for the gasless trade lifecycle |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [json-ld/0x-context.jsonld](json-ld/0x-context.jsonld) | Linked-data context for 0x entities (SwapQuote, GaslessTrade, CrossChainQuote, etc.) |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [rules/0x-rules.yml](rules/0x-rules.yml) | Lint rules enforcing the 0x API conventions (header auth, kebab-case paths, camelCase params, namespaced operationIds) |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/0x-api-swap.yaml](capabilities/0x-api-swap.yaml) | Swap surface (5 operations, REST + MCP exposers) |
| [capabilities/0x-api-gasless.yaml](capabilities/0x-api-gasless.yaml) | Gasless surface (6 operations, REST + MCP exposers) |
| [capabilities/0x-api-trade-analytics.yaml](capabilities/0x-api-trade-analytics.yaml) | Trade Analytics surface (2 operations) |
| [capabilities/0x-api-sources.yaml](capabilities/0x-api-sources.yaml) | Sources surface (1 operation) |
| [capabilities/0x-cross-chain-cross-chain.yaml](capabilities/0x-cross-chain-cross-chain.yaml) | Cross-Chain surface (5 operations) |

### Examples

| Example | Description |
|---------|-------------|
| [examples/0x-swap-allowance-holder-get-price-example.json](examples/0x-swap-allowance-holder-get-price-example.json) | Indicative price for WETH→USDC on Ethereum |
| [examples/0x-swap-allowance-holder-get-quote-example.json](examples/0x-swap-allowance-holder-get-quote-example.json) | Firm quote with calldata (WETH→USDC on Base) |
| [examples/0x-swap-permit2-get-quote-example.json](examples/0x-swap-permit2-get-quote-example.json) | Permit2 quote with EIP-712 typed data |
| [examples/0x-swap-get-chains-example.json](examples/0x-swap-get-chains-example.json) | Supported chains for the Swap API |
| [examples/0x-gasless-get-quote-example.json](examples/0x-gasless-get-quote-example.json) | Gasless USDC→WETH quote |
| [examples/0x-gasless-submit-trade-example.json](examples/0x-gasless-submit-trade-example.json) | Submit a signed gasless trade |
| [examples/0x-gasless-get-status-example.json](examples/0x-gasless-get-status-example.json) | Poll a gasless trade status |
| [examples/0x-cross-chain-get-quotes-example.json](examples/0x-cross-chain-get-quotes-example.json) | Bridge USDC Ethereum → Base via Across vs Relay |
| [examples/0x-trade-analytics-swap-example.json](examples/0x-trade-analytics-swap-example.json) | Two days of integrator swap trades |
| [examples/0x-sources-get-sources-example.json](examples/0x-sources-get-sources-example.json) | Enabled liquidity sources on Ethereum |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [vocabulary/0x-vocabulary.yml](vocabulary/0x-vocabulary.yml) | 0x domain vocabulary (Swap, Gasless, Permit2, Settler, RFQ, Trade Surplus, etc.) |

### Plans, Rate Limits, FinOps

| Artifact | Description |
|----------|-------------|
| [plans/0x-plans-pricing.yml](plans/0x-plans-pricing.yml) | API Commons Plans — Free / Standard ($1k/mo + 0.15%) / Custom ($2.5k+/mo) tiers |
| [rate-limits/0x-rate-limits.yml](rate-limits/0x-rate-limits.yml) | API Commons Rate Limits — per-tier RPS envelopes (1/5/100 RPS) plus per-quote freshness window |
| [finops/0x-finops.yml](finops/0x-finops.yml) | FinOps Framework / FOCUS 1.3 mapping for subscription, swap fee, trade surplus, and integrator monetisation |

## AI Tooling

| Tool | URL |
|------|-----|
| MCP Server | [https://docs.0x.org/_mcp/server](https://docs.0x.org/_mcp/server) |
| Claude Code Skill (`0x-api`) | [https://github.com/0xProject/0x-ai](https://github.com/0xProject/0x-ai) |
| Install command | `npx skills add 0xProject/0x-ai` |

## SDKs & Libraries

| Library | URL |
|---------|-----|
| 0x Parser (TypeScript) | [https://github.com/0xProject/0x-parser](https://github.com/0xProject/0x-parser) — published as [`@0x/0x-parser`](https://www.npmjs.com/package/@0x/0x-parser) on npm |
| TypeScript OpenAPI SDK template | [https://github.com/0xProject/0x-swap-ts-sdk-migration](https://github.com/0xProject/0x-swap-ts-sdk-migration) |
| Code Examples Collection | [https://github.com/0xProject/0x-examples](https://github.com/0xProject/0x-examples) |
| 0x Settler Contracts | [https://github.com/0xProject/0x-settler](https://github.com/0xProject/0x-settler) |

## Supported Chains

**Swap & Gasless (canonical EVM chain IDs):** Ethereum (1), Abstract (2741), Arbitrum (42161), Avalanche (43114), Base (8453), Berachain (80094), BNB (56), HyperEVM (999), Ink (57073), Linea (59144, Swap only), Mantle (5000), Monad (143), Optimism (10), Plasma (9745), Polygon (137), Scroll (534352), Sonic (146), Tempo (4217), Unichain (130), World Chain (480).

**Cross-Chain destinations also include:** Solana, HyperCore, Tron (with virtual chain IDs documented at [supported-chains](https://docs.0x.org/introduction/supported-chains)).

## Scope

- **x-type:** company
- **x-tier:** 1 (commercial DEX aggregator with full product surface)
- **Tags:** Cryptocurrency, DeFi, DEX Aggregator, Swap, Gasless, Cross-Chain, Permit2, Liquidity, Trade Analytics, Web3, Settlement, Smart Contracts

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

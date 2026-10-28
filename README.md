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

0x is the institutional-grade DEX aggregation and crypto liquidity infrastructure platform that powers token swaps inside hundreds of consumer wallets, exchanges, and onchain apps. The 0x API surface aggregates 150+ liquidity sources — public AMMs and exclusive professional market makers — across 20+ EVM chains, exposing four primary products: the Swap API (AllowanceHolder and Permit2 flows) for on-chain swaps, the Gasless API for swaps with no native gas token, the Cross-Chain API for any-token any-chain bridging across 16+ providers, and the Trade Analytics API for monetisation and reporting. Settlement is performed by the 0x Settler smart contracts using the Permit2 standard, and integrators get a unified API key, a TypeScript SDK, an official Agent Skill, and an MCP server for AI-assisted development.

**Areas:** Cryptocurrency · DeFi · DEX Aggregator · Swap · Gasless · Cross-Chain · Permit2 · Liquidity · Trade Analytics · Web3 · Settlement · Smart Contracts

## 0x on APIs.io

Everything profiled for 0x is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/0x/](https://apis.io/providers/0x/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [0x Cross-Chain API](https://apis.io/apis/0x/0x-cross-chain-api/) — Cross-Chain API endpoints
- [0x Gasless API](https://apis.io/apis/0x/0x-gasless-api/) — Gasless API endpoints
- [0x Sources API](https://apis.io/apis/0x/0x-sources-api/) — Sources API endpoints
- [0x Swap API](https://apis.io/apis/0x/0x-swap-api/) — Swap API endpoints
- [0x Trade Analytics API](https://apis.io/apis/0x/0x-trade-analytics-api/) — Trade Analytics API endpoints

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [0x](https://apis.io/servers/0x/0x/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [0X Agentic Access](https://apis.io/agentic-access/0x/0x-agentic-access/)

#### JSON Schema (9)

The data models the API reads and writes.

- [0x Cross-Chain Quote](https://apis.io/schemas/0x/0x-cross-chain-quote/)
- [0x API Error](https://apis.io/schemas/0x/0x-error/)
- [0x Gasless Trade](https://apis.io/schemas/0x/0x-gasless-trade/)
- [0x Gasless Trade Status](https://apis.io/schemas/0x/0x-gasless-trade-status/)
- [0x Liquidity Source](https://apis.io/schemas/0x/0x-liquidity-source/)
- [0x Supported Chain](https://apis.io/schemas/0x/0x-supported-chain/)
- [0x Swap Price](https://apis.io/schemas/0x/0x-swap-price/)
- [0x Swap Quote](https://apis.io/schemas/0x/0x-swap-quote/)
- [0x Trade Analytics Record](https://apis.io/schemas/0x/0x-trade-analytics-record/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [0X Gasless Trade Structure](https://apis.io/json-structure/0x/0x-gasless-trade-structure/)
- [0X Swap Quote Structure](https://apis.io/json-structure/0x/0x-swap-quote-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [0X Context](https://apis.io/jsonld/0x/0x-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [0x Domain Vocabulary](https://apis.io/vocabularies/0x/0x-vocabulary/)

#### Examples (10)

Example requests and responses.

- [0X Cross Chain Get Quotes Example](https://apis.io/examples/0x/0x-cross-chain-get-quotes-example/)
- [0X Gasless Get Quote Example](https://apis.io/examples/0x/0x-gasless-get-quote-example/)
- [0X Gasless Get Status Example](https://apis.io/examples/0x/0x-gasless-get-status-example/)
- [0X Gasless Submit Trade Example](https://apis.io/examples/0x/0x-gasless-submit-trade-example/)
- [0X Sources Get Sources Example](https://apis.io/examples/0x/0x-sources-get-sources-example/)
- [0X Swap Allowance Holder Get Price Example](https://apis.io/examples/0x/0x-swap-allowance-holder-get-price-example/)
- [0X Swap Allowance Holder Get Quote Example](https://apis.io/examples/0x/0x-swap-allowance-holder-get-quote-example/)
- [0X Swap Get Chains Example](https://apis.io/examples/0x/0x-swap-get-chains-example/)
- [0X Swap Permit2 Get Quote Example](https://apis.io/examples/0x/0x-swap-permit2-get-quote-example/)
- [0X Trade Analytics Swap Example](https://apis.io/examples/0x/0x-trade-analytics-swap-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [0x Cross-Chain API](https://apis.io/collections/0x/open-0x-cross-chain-api/)
- [0x Cross-Chain Gasless API](https://apis.io/collections/0x/open-0x-gasless-api/)
- [0x Cross-Chain Sources API](https://apis.io/collections/0x/open-0x-sources-api/)
- [0x Cross-Chain Swap API](https://apis.io/collections/0x/open-0x-swap-api/)
- [0x Cross-Chain Trade Analytics API](https://apis.io/collections/0x/open-0x-trade-analytics-api/)
- [0x Cross-Chain API](https://apis.io/collections/0x/postman-0x-cross-chain-api/)
- [0x Cross-Chain Gasless API](https://apis.io/collections/0x/postman-0x-gasless-api/)
- [0x Cross-Chain Sources API](https://apis.io/collections/0x/postman-0x-sources-api/)
- [0x Cross-Chain Swap API](https://apis.io/collections/0x/postman-0x-swap-api/)
- [0x Cross-Chain Trade Analytics API](https://apis.io/collections/0x/postman-0x-trade-analytics-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [0x — jsonschema rules](https://apis.io/rules/0x/0x-jsonschema-spectral-rules/)
- [0x API Rules](https://apis.io/rules/0x/0x-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [0X Authentication](https://apis.io/security/0x/0x-authentication/)
- [0X Domain Security](https://apis.io/security/0x/0x-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [0X Plans Pricing](https://apis.io/plans/0x/0x-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [0X Rate Limits](https://apis.io/rate-limits/0x/0x-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [0X Finops](https://apis.io/finops/0x/0x-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://0x.org)
- [Documentation](https://docs.0x.org)
- [Pricing](https://0x.org/pricing)
- [Changelog](https://docs.0x.org/changelog)
- [Blog](https://0x.org/post)
- [GitHub](https://github.com/0xProject)
- [Status](https://status.0x.org)

## API Evangelist rating

**Kin Score 46.1** — developing · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.3 |
| Contract quality | 59.5 |
| Contract governance | 27.3 |
| Operational transparency | 42.1 |
| Developer ergonomics | 46.4 |
| Access clarity | 31.6 |

**Agent readiness 25.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | platform (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/0x/](https://apis.io/providers/0x/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for 0x: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/0x/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

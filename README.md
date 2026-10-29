# ConceptNet

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

ConceptNet is a freely available multilingual knowledge graph that gives computers access to common-sense knowledge. It represents over 13 million links between concepts across 100+ languages, drawing from crowd-sourced resources (Open Mind Common Sense, Wiktionary), expert-created resources (WordNet, JMDict), and games with a purpose (Verbosity, nadya.jp). The public REST API provides JSON-LD responses and receives over 50,000 daily hits. ConceptNet also powers Numberbatch, a set of multilingual word embeddings aligned across languages that outperform word2vec, GloVe, and fastText on standard benchmarks.

**Areas:** Knowledge Graph · Natural Language Processing · Semantic Web · Common Sense · Multilingual · Word Embeddings · Linked Data · Open Data

## ConceptNet on APIs.io

Everything profiled for ConceptNet is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/conceptnet/](https://apis.io/providers/conceptnet/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [ConceptNet REST API](https://apis.io/apis/conceptnet/conceptnet-rest-api/) — The ConceptNet REST API exposes the full ConceptNet 5 knowledge graph via JSON-LD endpoints. Consumers can look up concept nodes by language and term, query…
- [ConceptNet Concepts API](https://apis.io/apis/conceptnet/conceptnet-concepts-api/) — Look up concept nodes in the knowledge graph
- [ConceptNet Edges API](https://apis.io/apis/conceptnet/conceptnet-edges-api/) — Access individual edge (assertion) records
- [ConceptNet Query API](https://apis.io/apis/conceptnet/conceptnet-query-api/) — Complex multi-parameter edge queries
- [ConceptNet Relations API](https://apis.io/apis/conceptnet/conceptnet-relations-api/) — Browse edges grouped by relation type
- [ConceptNet Similarity API](https://apis.io/apis/conceptnet/conceptnet-similarity-api/) — Semantic similarity and relatedness using Numberbatch embeddings
- [ConceptNet Sources API](https://apis.io/apis/conceptnet/conceptnet-sources-api/) — Access provenance and source information
- [ConceptNet Utilities API](https://apis.io/apis/conceptnet/conceptnet-utilities-api/) — URI normalization and text standardization

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Conceptnet Agentic Access](https://apis.io/agentic-access/conceptnet/conceptnet-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [ConceptNet Concept Node](https://apis.io/schemas/conceptnet/concept-node/)
- [ConceptNet Edge](https://apis.io/schemas/conceptnet/edge/)
- [ConceptNet Relatedness Result](https://apis.io/schemas/conceptnet/relatedness/)

#### Examples (5)

Example requests and responses.

- [Get Concept Node](https://apis.io/examples/conceptnet/get-concept-node/)
- [Get Related Concepts](https://apis.io/examples/conceptnet/get-related-concepts/)
- [Get Relatedness](https://apis.io/examples/conceptnet/get-relatedness/)
- [Normalize Uri](https://apis.io/examples/conceptnet/normalize-uri/)
- [Query Edges](https://apis.io/examples/conceptnet/query-edges/)

#### Collections (7)

Postman and Open Collection request collections.

- [ConceptNet REST Concepts API](https://apis.io/collections/conceptnet/open-conceptnet-concepts-api/)
- [ConceptNet REST Concepts Edges API](https://apis.io/collections/conceptnet/open-conceptnet-edges-api/)
- [ConceptNet REST Concepts Query API](https://apis.io/collections/conceptnet/open-conceptnet-query-api/)
- [ConceptNet REST Concepts Relations API](https://apis.io/collections/conceptnet/open-conceptnet-relations-api/)
- [ConceptNet REST Concepts Similarity API](https://apis.io/collections/conceptnet/open-conceptnet-similarity-api/)
- [ConceptNet REST Concepts Sources API](https://apis.io/collections/conceptnet/open-conceptnet-sources-api/)
- [ConceptNet REST Concepts Utilities API](https://apis.io/collections/conceptnet/open-conceptnet-utilities-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [ConceptNet — jsonschema rules](https://apis.io/rules/conceptnet/conceptnet-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Conceptnet Domain Security](https://apis.io/security/conceptnet/conceptnet-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Conceptnet Plans Pricing](https://apis.io/plans/conceptnet/conceptnet-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Conceptnet Rate Limits](https://apis.io/rate-limits/conceptnet/conceptnet-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Conceptnet Finops](https://apis.io/finops/conceptnet/conceptnet-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://conceptnet.io)
- [Documentation](https://github.com/commonsense/conceptnet5/wiki/API)
- [Getting started](https://github.com/commonsense/conceptnet5/wiki)
- [Support](https://groups.google.com/g/conceptnet-users)
- [GitHub](https://github.com/commonsense)

## API Evangelist rating

**Kin Score 27.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 48.4 |
| Contract governance | 9.8 |
| Operational transparency | 10.5 |
| Developer ergonomics | 26.2 |
| Access clarity | 5.3 |

**Agent readiness 27.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 5.9** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/conceptnet/](https://apis.io/providers/conceptnet/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ConceptNet: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/conceptnet/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

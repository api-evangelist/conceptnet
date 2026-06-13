# ConceptNet

ConceptNet is a freely available multilingual knowledge graph that gives computers access to common-sense knowledge. It represents over 13 million links between concepts across 100+ languages, drawing from crowd-sourced resources (Open Mind Common Sense, Wiktionary), expert-created resources (WordNet, JMDict), and games with a purpose (Verbosity, nadya.jp).

The public REST API at `api.conceptnet.io` provides JSON-LD responses, requires no authentication, and receives over 50,000 daily hits. ConceptNet also powers Numberbatch, a set of multilingual word embeddings that outperform word2vec, GloVe, and fastText on standard benchmarks.

- **Website:** https://conceptnet.io
- **API Base URL:** https://api.conceptnet.io
- **API Documentation:** https://github.com/commonsense/conceptnet5/wiki/API
- **GitHub:** https://github.com/commonsense/conceptnet5
- **License:** CC BY-SA 4.0

## Key Endpoints

| Endpoint | Description |
|---|---|
| `GET /c/{language}/{term}` | Look up all edges for a concept node |
| `GET /query` | Query edges by relation, start, end, or source |
| `GET /related/c/{language}/{term}` | Get semantically related terms (Numberbatch) |
| `GET /relatedness?node1=…&node2=…` | Score pairwise semantic similarity (0–1) |
| `GET /uri?language=…&text=…` | Normalize text to a canonical ConceptNet URI |

## Rate Limits

- 3,600 requests per hour
- 120 requests per minute (burst)
- `/related` and `/relatedness` count as 2 requests each
- No API key required

## Files

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/conceptnet-plans-pricing.yml` — Pricing tiers (free / self-hosted)
- `rate-limits/conceptnet-rate-limits.yml` — Rate limit details
- `finops/conceptnet-finops.yml` — Cost optimization strategies

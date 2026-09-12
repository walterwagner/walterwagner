# Walter Wagner

Software, data validation and infrastructure projects with reproducible checks.

## Independent projects

| Project | What it does | Try it |
| --- | --- | --- |
| [Inference Chip Index](https://github.com/walterwagner/inference-chip-index) | Source-linked MLPerf comparisons, workload filters, data provenance and a documented API. | [Live demo](https://inference-chip-index.clonadowalter.workers.dev/) |
| [Probability Detective](https://github.com/walterwagner/probability-detective) | Interactive coin and dice experiments, fair-game design and reproducible mathematical tests. | [Live lesson](https://probability-detective.clonadowalter.workers.dev/) |

Both repositories include setup instructions, validation evidence and known limitations.

## Open-source contributions

- [Qdrant catalog for Plural](https://github.com/pluralsh/scaffolds/pull/74): persistent vector storage and stable API authentication.
- [Valkey catalog for Plural](https://github.com/pluralsh/scaffolds/pull/77): stable ACL credentials, retained storage and authenticated readiness.
- [NATS JetStream catalog for Plural](https://github.com/pluralsh/scaffolds/pull/78): Secret-backed authentication and persistent message streams.
- [Meilisearch catalog for Plural](https://github.com/pluralsh/scaffolds/pull/79): managed master-key authentication and persistent search indexes.

The linked pull requests show their current review and merge status.

## Development approach

Small, independently testable components; explicit data and security boundaries; automated checks followed by runtime verification and documented validation limits.

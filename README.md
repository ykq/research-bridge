# Research Bridge

Research Bridge is a portable Codex skill for finding a useful connection between an active problem and research from another field.

It asks a practical question: **has another field already studied the mechanism that is giving us trouble?** A result is useful only when it can change a decision, measurement, intervention, or small test. Surface analogies do not count.

## What it produces

By default, the skill returns one strong bridge in plain language:

- why the paper matters;
- a direct link to the deepest stable article location inspected;
- one concrete change to a component, data surface, decision, or workflow step;
- one small comparison that can test the idea;
- the biggest reason the result may not transfer.

When a paper contains a reusable pattern, the skill may suggest it as an **inactive motif**: a hypothesis to investigate, not a label or production rule. For example, Bitcoin's parent-linked history can inspire a tamper-evident provenance motif without importing mining, currency, proof-of-work, or longest-chain consensus.

## Install

Clone this repository into a `research-bridge` directory inside your Codex skills directory, or copy the repository root there. The installed layout must keep `SKILL.md`, `agents/`, and `references/` together.

Then ask for a cross-domain research connection, for example:

> Find outside research that could help us distinguish shared behavior from shared identity in this transaction graph.

The skill can also activate when an unresolved mechanism, incentive, network structure, attribution problem, measurement problem, or failure mode would benefit from outside literature.

## Evidence and privacy

- Primary papers support substantive claims; reviews help map a field.
- Metadata alone is treated as an unchecked lead.
- Every claim-bearing source gets a canonical reader-facing link and an inspection label.
- Private names, addresses, identifiers, credentials, local paths, personal measurements, and unpublished results are removed before external searching.
- If the question cannot be generalized safely, the skill does not make an external request.
- A bridge proposes a hypothesis and test. It does not prove that a result transfers unchanged.

The skill does not include a scheduler, notification route, persistent database, private infrastructure, or automatic production changes.

## Files

- `SKILL.md` — activation, evidence, privacy, and output contract.
- `references/lbd-method.md` — the mechanism-first literature discovery method.
- `references/scenario-matrix.md` — activation and failure examples.
- `agents/openai.yaml` — Codex skill metadata.
- `IMPLEMENTATIONS.md` — public component registry and release boundary.

## License

MIT. See `LICENSE`.

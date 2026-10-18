---
name: research-bridge
description: This skill should be used to find concise, cited connections between an active problem and research from another field when a shared mechanism could change a decision or suggest a useful test. Use for explicit literature-based discovery and unresolved mechanism, incentive, network, measurement, or failure problems. Do not use for routine lookups, surface analogies, fixed-format outputs, or when the user asks not to research.
---

# Research Bridge

Find outside research that studies the same underlying mechanism as the active problem. A bridge is a source of hypotheses and tests, not proof that a result transfers unchanged.

## Activation gate

Activate only when all three conditions hold:

1. The active problem contains a generalizable unresolved mechanism, incentive, network structure, attribution problem, measurement problem, or failure mode.
2. A genuinely different field studies the same causal or structural relationship, not merely similar words or subject matter.
3. A finding from that field could change a decision, measurement, intervention, or bounded test in the active work.

If any condition fails, continue the main task without a research bridge.

Keep the user's main task first. Do not add a research aside to routine implementation, settled documentation lookup, narrow source fetching, structured-only output, or a request not to research.

## Protect private context

Build literature queries from general concepts. Remove private names, addresses, transaction hashes, credentials, local paths, personal measurements, unpublished results, and rare combinations that could reconstruct a private record. If the question cannot be generalized safely, do not make an external request.

Do not create a timer, database, notification, backlog, or persistent task unless the user explicitly requests one.

## Build a real bridge

Use an A–B–C chain internally:

- **A — active problem:** State the unresolved problem in general terms.
- **B — shared mechanism:** Explain the causal or structural relationship shared by both fields.
- **C — outside literature:** Find a genuinely different field that studies B.

Read [lbd-method.md](./references/lbd-method.md) before searching. Use [scenario-matrix.md](./references/scenario-matrix.md) when activation, privacy, or evidence handling is unclear.

For cross-domain discovery, search without the active domain's vocabulary first. Explore neighboring fields, terminology from review abstracts, and citation trails. A result is useful only if it contributes a mechanism, measurement, evaluation, intervention, or failure boundary that could change the active investigation. Shared words or a surface analogy are not enough.

## Evidence standards

- Use primary papers for substantive claims and reviews to map a field.
- Metadata may establish only bibliographic facts. Inspect an abstract or full text before making a mechanism, effect, causal, or transfer claim.
- Check whether each claim-bearing source is retracted or has a relevant update or correction.
- Label preprints clearly and do not call them peer reviewed without a separate publication record.
- Include contradictory or boundary evidence when found.
- Give every claim-bearing source one human-readable, canonical link to the inspected article, abstract, or anchored full-text section. Do not use a search-result URL. Do not make a metadata page the only link when a DOI, publisher article, PubMed, Europe PMC, or preprint article page exists.
- Map every substantive mechanism, effect, causal, or transfer claim to an inspected source. For each source record the supported claim, title, stable identifier, canonical direct URL, publication status, retrieval date, inspection level (`abstract` or `full text`), and the bridge element it supports.
- Treat a metadata-only record as an unchecked lead. It may support bibliographic facts, but it may not support a mechanism or transfer claim.

If a required source, abstract, or retraction check is unavailable, distinguish an unchecked lead from a supported finding. Do not fill evidence gaps with confident prose.

## Make the transfer useful

Explain what the paper changes in practice. If the user has provided a system, workflow, or codebase, the stack application must name the concrete component, data surface, decision, or workflow step affected and propose one action there. Otherwise say that no stack context was supplied and give a general application.

When a paper describes a reusable behavior or failure pattern, include an inactive candidate motif with four fields: plain-language name, hypothesis, observable local pattern, and evidence boundary. Do not activate a label, rule, or production decision from literature alone.

A paper can supply a motif even when its full system should not transfer. For example, Bitcoin's parent-linked, tamper-evident history can inspire an inactive provenance motif for a workflow; proof-of-work, mining, currency, and longest-chain consensus do not come along with it. Name both the useful mechanism and the parts that stay behind.

Propose one small test with an observable comparison. Separate what was directly observed from what was inferred.

## Write for a reader who has not read the paper

Keep A–B–C as internal reasoning. Write at an ELI5 level without becoming inaccurate: explain the finding in ordinary sentences before naming a metric, define every necessary technical term at first use, and state what every reported number means in practice. Use plain headings, short sentences, and concrete verbs.

Default to the single strongest bridge. Add another only when it changes a different decision or suggests a different test. Lead with one plain sentence that says why the paper matters. Do not repeat the same setup, paper metadata, or caveat in multiple sections.

Make the stack move crisp: name one component or data surface, one change, and why it helps. Prefer a small edit the user could actually try over a general research program.

Link the paper title directly to the deepest stable article location you inspected. Prefer an anchored full-text section when the publisher supports stable anchors. Otherwise link the article or PDF and name the inspected section or page beside it. Never imply that an abstract link reaches the full methods.

Use this shape when a bridge passes:

```markdown
Research bridge

Takeaway: one plain sentence on why this matters.
Paper: linked title; the finding in plain English; inspected section or page.
Try this in your stack: component or data surface; one concrete change; why.
First small test: comparison; observable result.
Candidate motif (when applicable): name; hypothesis; observable pattern; evidence boundary; status: inactive.
Evidence note: claim; stable ID; publication status; retrieved date; abstract/full text.
How useful: n/10 — one sentence.
Biggest caveat: one sentence.
```

The usefulness score measures mechanism fit, decision proximity, actionability, and non-obvious information gain. It is not confidence, truth probability, or evidence quality.

Avoid repeating the same problem, mechanism, and source combination in one conversation.

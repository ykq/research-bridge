# Literature-based discovery method

Use this reference to formulate the bridge, choose sources, and keep novelty separate from evidence strength.

## Useful mechanism vocabulary

Choose the closest accurate concept rather than inventing synonyms:

- adversarial adaptation
- anomaly detection
- causal inference
- collective behavior
- contagion or diffusion
- coordination under partial observability
- feedback and control
- measurement error or noisy attribution
- network structure
- repeated-game incentives
- resource allocation or auctions
- robustness or failure propagation
- selection bias

Use a different term when none of these fits, but define it plainly.

## A–B–C formulation

1. Strip private and domain-specific identifiers from the active problem.
2. Write the shared mechanism as a causal or structural sentence: “When X changes, Y changes because Z.” Stop if this cannot be stated without hand-waving.
3. Search a different field for that mechanism. Begin with mechanism terms rather than the active domain label.
4. Follow terminology and citations from relevant reviews or abstracts.
5. Return to the active problem with one transferable measurement, intervention, model, or failure test and one reason the transfer may break.

Novelty means the outside source contributes something not already explicit in the active problem. Unfamiliar vocabulary alone is not novelty.

## Search patterns

- `mechanism term` + review, experiment, model, intervention, failure, boundary condition
- `measurement problem` + validation, misclassification, latent class, capture-recapture, missing-not-at-random
- `network structure` + diffusion, threshold, cascade, resilience, centrality, multiplex
- `adversarial adaptation` + concept drift, evasion, arms race, Goodhart, strategic classification
- `repeated-game incentives` + cooperation, punishment, reputation, signaling, mechanism design

## Evidence levels

- **Metadata inspected:** supports identity, date, venue, identifier, and publication status only.
- **Abstract inspected:** may support the mechanism or reported effect explicitly stated there.
- **Full text inspected:** may support methods, results, boundary conditions, and contradictions actually present.
- **Independent corroboration inspected:** supports consistency across sources but does not remove study-design limits.

For each substantive statement, record the claim, title, stable identifier, publication status, retrieval date, whether an abstract or full text was inspected, and which part of the bridge it supports. Keep a reader-facing link to the inspected article or abstract.

## Usefulness score

- **1–3:** adds a concrete term, question, or modest test.
- **4–6:** materially sharpens the problem or test.
- **7–9:** has near-term investigative value.
- **10:** directly changes how the problem should be framed or investigated.

Score usefulness, not certainty. Describe evidence strength and limitations separately.

## Plain-language handoff

Keep the A–B–C structure private. Explain what the paper found, what could transfer, what small test to run, and what could make the transfer fail. Translate each technical metric into its practical consequence.

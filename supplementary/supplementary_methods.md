# Supplementary Methods Evidence Reconstruction Protocol

## Data sources and historical scope

The reconstruction uses only the V1.0 frozen evidence library and its provenance records. Historical evidence acquisition was an iterative directed audit using database records, article full text where available, citation chasing, dataset and supplement checks, and manual context verification. Because complete prospectively recorded search strings are not available for every historical subtask, this protocol does not claim PRISMA completeness. The process was retrospectively standardized during the V1.0 freeze.

## Edge schema

Each edge requires source, target, direction, species, cell type, disease/model context, stimulus, intervention, readout, directness, primary source identity, context match, and negative/contradictory evidence status. Reporter, RNA/protein response, gain/loss, and rescue evidence are recorded separately. Associations are not promoted to causal edges.

## Grade definitions

Direct, cross-context, computational, hypothesis, and unresolved are mutually exclusive manuscript grades. Cross-context evidence cannot be upgraded by combining several non-identical records. Computational results do not become experimental evidence. A hypothesis remains unvalidated until its specified experiment is positive.

## Context transfer and compartment rules

Species, cell type, stimulus, disease, and intervention form the context tuple. A mismatch downgrades evidence. DAKIKI is a B-lymphoblast surrogate, not a mature plasma-cell or renal model. IL-1 mesangial stimulation is not IgAN immune-complex stimulation. Mesangial intracellular mechanisms are not assigned to podocytes without independent evidence.

## Negative and contradictory evidence rules

No qualifying record is reported as unresolved rather than as biological absence. Identity mismatch, such as let-7a/e rather than miR-98, is retained as non-substitutable evidence. Contradictions remain in the registry and constrain wording.

## Claim freeze and historical computational provenance

The revised paper has four main claims. Exploratory topology work during historical model development was uncalibrated and is not interpreted as pharmacologic or clinical probability. No drug simulation, Monte Carlo result, patient prediction, or dynamic fitted model is included in the manuscript.

## Materials and responsibility

Frozen matrices, registries, scripts, and model provenance are prepared for repository deposition before submission. No repository URL is asserted here. AI-assisted tools supported organization and drafting; authors retain responsibility for primary-source verification, evidence grading, and final interpretation.

# IgAN miR-98-5p / TNFAIP3-A20 regulatory decoupling hypothesis

## Current public release

**Scientific version:** V1.7.1
**GitHub release:** v1.1.0 - Compartment-Specific Rationale and Gate 0 Update

This repository documents an evidence-constrained mechanistic hypothesis and its falsification architecture. It does not provide medical advice, establish therapeutic efficacy, or present a validated therapeutic intervention.

One scientific project uses one GitHub repository and one Zenodo version lineage, while retaining multiple immutable scientific versions. The historical `v1.0.0` release documents the V1.6 submission evidence package. The current `v1.1.0` release documents the V1.7.1 scientific architecture update.

## Core architecture

The project tests two conditional levels of regulatory decoupling.

1. **Compartment-specific decoupling:** peripheral/systemic miR-98-5p biology is not assumed to be the same as renal resident-cell miR-98-5p biology.
2. **Target-specific decoupling:** only after a desired renal miR-98-5p effect and a detrimental TNFAIP3/A20 trade-off are demonstrated in the relevant context may selective target-site protection be tested.

No target-site protector is validated. No therapeutic efficacy is established. No clinical recommendation is made.

## Gate architecture

| Gate | Status | Role |
|---|---|---|
| Gate 0A | Unresolved | Auxiliary phenotype mapping |
| Gate 0B | Unresolved | **True functional go/no-go** |
| Gate 0C | Exploratory unresolved | Auxiliary biogenesis module |
| Gate A | Unresolved | Direct miR-98-5p to TNFAIP3/A20 test in relevant human renal context |
| Gate B | Unresolved | Functional importance of A20 preservation |
| Gate C | Premature pending Gate 0B, A, and B | Conditional selective target-site-protection test |

Gate 0 passes only when Gate 0B is positive. Gate 0A and Gate 0C do not pass Gate 0. A negative Gate 0B stops the renal miR-98 augmentation strategy. Positive Gates 0B, A, B, and C could justify further proof-of-concept development; they would not by themselves establish therapy or clinical efficacy.

## Evidence boundaries

Evidence is graded by disease, species, cell type, stimulus, intervention, endpoint, and directness. IgAN PBMC is not a renal resident cell; lupus nephritis renal tissue is not IgAN renal tissue; human mesangial IP15 cells are not primary IgAN mesangial cells; and developmental/neural LIN28 biology is not IgAN renal LIN28 dysregulation.

The V1.7.1 evidence matrix records miR-98 to BACH1 as direct cross-disease human renal evidence and BACH1 to NF-kappaB/p65 activity as direct functional human mesangial cross-context evidence. These records do not establish an IgAN primary-mesangial mechanism or an IgAN immune-complex-stimulation result. The Viswanathan and Kawahara LIN28 records are retained separately; neither establishes IgAN renal LIN28 dysregulation.

## Contents

- `V1.7.1_PUBLIC_EVIDENCE_PACKAGE/`: V1.7.1 manuscript, evidence matrix, new-reference audit, Gate specification, claim freeze, context-transfer audit, overclaim audit, Figure 1, reference QA, provenance, and checksums.
- Historical root-level files: preserved V1.0.0 / V1.6 evidence package materials.
- `RELEASE_NOTES_v1.1.0.md`: release-specific summary and evidence-boundary update.

## Historical script provenance

Historical development-stage scripts are retained for project-history transparency where applicable. Their execution provenance relative to the manuscript conclusions has not been fully verified; they are therefore not presented as code used to generate manuscript results.

## Citation and licensing

The project-level Zenodo Concept DOI is [10.5281/zenodo.22686375](https://doi.org/10.5281/zenodo.22686375). The immutable historical v1.0.0 version DOI is `10.5281/zenodo.22686376`.

- Author-generated code, where present: [MIT License](LICENSE).
- Author-original evidence matrices and derived evidence tables: [CC BY 4.0](EVIDENCE_DATA_LICENSE.md).
- Neither license applies to third-party publications, publisher figures, PDFs, supplementary materials, or other copyrighted source material cited by this project.

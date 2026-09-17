# IgAN miR-98-5p / TNFAIP3-A20 regulatory decoupling hypothesis

## Public release v1.1.0

**Scientific version:** V1.7.1  
**Release:** v1.1.0 - Compartment-Specific Rationale and Gate 0 Update

This repository documents an evidence-constrained mechanistic hypothesis and its falsification architecture. It does not provide medical advice, establish therapeutic efficacy, or present a validated therapeutic intervention.

The V1.7.1 update introduces two levels of regulatory decoupling:

1. **Compartment-specific decoupling:** peripheral/systemic miR-98-5p biology is not assumed to be the same as renal resident-cell miR-98-5p biology.
2. **Target-specific decoupling:** only if renal miR-98-5p has a demonstrated desired effect and also directly suppresses TNFAIP3/A20 in the relevant context may selective target-site protection be tested.

No target-site protector is validated. No therapeutic efficacy is established. No clinical recommendation is made.

## Evidence boundary

The manuscript is prepared for journal submission; it is not an accepted, published, or peer-reviewed article. It does not establish renal miR-98-5p deficiency in IgA nephropathy (IgAN), an IgAN renal LIN28 defect, a direct miR-98-5p to TNFAIP3/A20 relation in human IgAN mesangial cells, a delivery method, fibrosis reversal, clinical benefit, or a patient-level digital twin.

Evidence grades distinguish direct evidence in the stated context, cross-context evidence, hypothesis, and unresolved evidence. Disease, species, cell type, stimulus, intervention, and readout are part of every interpretation. In particular, IgAN PBMC is not a renal resident cell; lupus nephritis renal tissue is not IgAN renal tissue; human mesangial IP15 cells are not primary IgAN mesangial cells; and developmental/neural LIN28 biology is not IgAN renal LIN28 dysregulation.

## Gate architecture

| Gate | Question | Status | Role |
|---|---|---|---|
| Gate 0A | Renal phenotype/localization mapping | Unresolved | Auxiliary phenotype mapping |
| Gate 0B | Functional renal miR-98-5p actionability in an IgAN-relevant human context | Unresolved | **True functional go/no-go** |
| Gate 0C | LIN28/biogenesis exploration | Unresolved | Auxiliary/exploratory |
| Gate A | Direct miR-98-5p to TNFAIP3/A20 regulation in a relevant human renal context | Unresolved | Required only after Gate 0B positive |
| Gate B | Functional importance of A20 preservation under IgAN-relevant stimulation | Unresolved | Required only after Gate A positive |
| Gate C | Selective target-site protection | Not tested; premature pending Gates 0B, A, and B | Conditional implementation test |

Gate 0 passes only if Gate 0B is positive. Gate 0A and Gate 0C do not pass Gate 0. A negative Gate 0B stops the renal miR-98 augmentation strategy. A positive Gate C may justify further proof-of-concept development; it does not establish therapy or clinical efficacy.

## Contents

- `MANUSCRIPT/`: the V1.7.1 scientific master manuscript in editable, PDF, and Markdown forms.
- `EVIDENCE/`: the V1.7.1 evidence matrix, targeted new-reference audit, and reference quality assurance.
- `HYPOTHESIS_ARCHITECTURE/`: Gate specification, frozen claims, context-transfer audit, and overclaim audit.
- `FIGURES/`: author-generated Figure 1 in high-resolution TIFF and PNG preview formats, with its legend.
- `PROVENANCE/`: release provenance, scientific status, and V1.6-to-V1.7.1 change log.

## BACH1 and LIN28 clarification

The evidence matrix records miR-98 to BACH1 as direct cross-disease human renal evidence in the human mesangial IP15 cell-line context. It records BACH1 to NF-kappaB/p65 activity as direct functional human mesangial cross-context evidence, based on BACH1 gain/loss, p-p65 readout, and an NF-kappaB inhibitor functional test. Neither record establishes a primary IgAN mesangial mechanism or IgAN immune-complex stimulation result.

LIN28 evidence is separated: Viswanathan et al. (2008) supports LIN28 inhibition of let-7-family processing, while Kawahara et al. (2011) supports LIN28 binding to pri/pre-miR-98 and inhibition of processing in a neural differentiation context. Neither establishes IgAN renal LIN28 dysregulation.

## Historical code provenance

Historical development-stage scripts remain available for project-history transparency where applicable. Their execution provenance relative to the manuscript results has not been fully verified; they are therefore not presented as code used to generate the manuscript conclusions. No historical development-stage scripts are duplicated in this v1.1.0 release.

## Licenses

- `LICENSE` retains the historical local MIT license for author-generated code, where applicable.
- `EVIDENCE_DATA_LICENSE.md` retains the CC BY 4.0 notice for author-original evidence matrices and derived evidence tables.
- Neither license applies to third-party publications, publisher figures, PDFs, supplementary materials, or other copyrighted source material cited by this project.

The locally available Zenodo metadata has an unresolved license field; release licensing must be verified by the author in the remote GitHub and Zenodo interfaces before publication.

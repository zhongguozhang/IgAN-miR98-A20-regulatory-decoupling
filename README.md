# Evidence and analysis materials for the miR-98-5p/TNFAIP3-A20 regulatory-decoupling hypothesis in IgA nephropathy

## Purpose and scope

This is a hypothesis and evidence repository. It makes the evidence basis, context boundaries, claim limitations, conceptual figures, and supplementary methods available for inspection. It is not a validated disease model or therapeutic-development package.

## Critical mechanistic boundary

The proposed miR-98-5p → TNFAIP3/A20 relation has **not** been directly demonstrated in human IgA-nephropathy mesangial cells. Evidence from other cell types is retained as cross-context evidence only and must not be treated as confirmation in human IgAN mesangial cells.

The hypothesis is deliberately gated:

- **Gate A:** test whether mature miR-98-5p directly regulates TNFAIP3/A20 in relevant human renal cells.
- **Gate B:** test whether A20 functionally constrains IgAN-relevant inflammatory signalling in those cells.
- **Gate C:** only if Gates A and B are positive and biologically relevant, test a hypothetical selective TNFAIP3 target-site-protection design.

A negative Gate A removes the rationale for the TNFAIP3-specific protection branch.

## Evidence grades and context rules

`Direct`, `cross-context`, `computational`, `hypothesis`, and `unresolved` are distinct evidence grades. Species, cell type, disease setting, stimulus, intervention, and readout are part of every interpretation. Do not promote cross-context findings to exact-context mechanisms. See `evidence/evidence_levels.md` and `evidence/context_grading_rules.md`.

## What this repository does not provide

- No therapeutic-efficacy simulation.
- No patient-specific digital twin.
- No clinical treatment recommendation.
- No validated target-site protector or therapeutic sequence.
- No claim that the central renal miR-98-5p/A20 mechanism has been verified.

## Code provenance limitation

The wider project contains 82 historical development-stage scripts. None has verified individual execution provenance as code used to generate manuscript results, and none is released in this repository. If development-stage utilities are released in a future repository version, they must be placed in `analysis_development/` and carry the following notice:

> These files are retained as development-stage analysis utilities. Historical execution provenance could not be verified for individual scripts. They should not be interpreted as the verified code used to generate the manuscript results.

Consequently, this release claims zero verified executed publication-relevant analysis scripts.

## Contents

- `evidence/`: frozen derived evidence, edge, claim, reference, and limitation tables.
- `supplementary/`: reconstruction methods, model-boundary documentation, and a release file manifest.
- `figures_source/`: author-generated conceptual evidence-status figures.
- `CITATION.cff`: citation metadata without an invented DOI.

## License

- Author-generated code, if present: [MIT License](LICENSE).
- Author-original evidence matrices and derived evidence tables: [CC BY 4.0](EVIDENCE_DATA_LICENSE.md).
- Neither license applies to third-party publications, publisher figures, PDFs, supplementary materials, or other copyrighted source material cited by the project.

## Citation and contact

Use `CITATION.cff`. A repository DOI has not been created. Contact: Zhongguo Zhang, zzg1974@foxmail.com.

# Research proposal

**Title:** Evaluating Analytics Project Selection Frameworks for Small and Medium-Sized Enterprises  
**Researcher:** Maryam Mafoud  
**Status:** Preliminary proposal — November 2026

## Problem and motivation

An SME considering several analytics initiatives needs a defensible basis for deciding which to pursue. Anticipated benefits, implementation effort, data readiness, uncertainty, and organisational priorities may point toward different choices. This project asks how a modest decision-support procedure could make those trade-offs explicit and reveal when a preferred project depends heavily on particular assumptions.

The initial literature includes a project-scoring framework by Langer and Pütterich (2024) and an integrative analytics framework by Bhardwaj et al. (2025). Their verified contributions and the limits of the present reading are recorded in the [literature review](../literature/review.md). The proposed focus on ranking sensitivity and decision transparency is a working research direction. Its novelty and the extent of any empirical-validation gap remain to be established through a broader review.

## Aim and scope

The aim is to evaluate selected approaches to analytics project selection and investigate a lightweight implementation suitable for exploratory use. The unit of analysis will initially be a candidate analytics project within one hypothetical SME context. The study will distinguish project ranking from portfolio optimisation: selecting a feasible combination of interdependent projects under a budget is outside the initial scope.

The SME definition, country or sector context, and inclusion of microenterprises will be specified before empirical work. Evidence about MSMEs will not automatically be treated as applicable to every SME population.

## Research questions

1. How can SMEs evaluate the expected value of different analytics projects?
2. How sensitive are project rankings to the weighting of evaluation criteria?
3. Can a lightweight decision-support framework improve the consistency and transparency of analytics project selection?

## Proposed methodology

### Phase 1: Literature review and scope refinement

Conduct the documented search in [literature/search-plan.md](../literature/search-plan.md). Extract the purpose, criteria, scoring procedure, context, evidence, and limitations of relevant frameworks. Select comparators based on relevance and sufficient methodological detail, not on whether they favour a proposed approach. Record source-specific evidence for every adopted criterion and clearly identify any new design assumption.

### Phase 2: Specification before implementation

Prepare a criterion dictionary with definitions, scoring anchors, benefit/cost direction, information required, and uncertainty notes. Potential dimensions include anticipated business benefit, strategic fit, implementation burden, data readiness, and risk. These are provisional design candidates, not an established or validated instrument. Check for overlapping criteria and double counting.

A weighted additive score is one candidate baseline: S(p) = sum_j w_j v_j(p), with non-negative weights summing to one and consistently oriented criterion values. This is a planned modelling choice, not a formula attributed to either starting paper. Define transformations and anchors before comparing projects. Discuss the assumptions of compensability and comparable scales. Treat mandatory feasibility requirements separately so that a high benefit score cannot compensate for an unacceptable constraint violation.

Weights will initially represent stated hypothetical preferences, not measured SME preferences. Missing evidence will be flagged; it will not silently become a zero score. If a published framework cannot be reproduced faithfully, document that limitation and label any adaptation explicitly.

### Phase 3: Exploratory computational evaluation

After fixing the protocol, construct a small set of clearly labelled hypothetical project scenarios, potentially covering inventory forecasting, sales reporting, and customer analysis. These are candidate examples only; no scenario data currently exist. Compare an equal-weight baseline, stated preference profiles, and any sufficiently specified literature-based comparator. Apply identical inputs where comparison is meaningful.

Vary weights while keeping them valid and vary uncertain scores separately. Report rank correlations, top-choice changes, ties, and switching thresholds. Preserve all scenarios, including cases where rankings are unstable or methods disagree. Reproducibility records will include input versions, parameters, software environment, random seeds if used, and commit identifiers.

### Phase 4: Optional human evaluation

RQ3 requires evidence beyond deterministic software output. If feasible, recruit consenting SME decision-makers for an exploratory comparison between an unstructured selection task and the proposed aid. Define eligibility, recruitment, sample-size rationale, task materials, and analysis before collecting data. Use matched tasks and counterbalanced order to reduce learning effects. Candidate measures include agreement across assessors, repeat-decision consistency, completeness of recorded rationales, ability to explain trade-offs, and task time.

Any applicable institutional ethics review, consent process, and confidentiality protections must precede recruitment. No participants or business partners are currently secured. If practitioner access is unavailable, restrict conclusions to scenario behaviour and documentation traceability; leave claims of improved human decision-making unresolved.

## Expected contributions, conditional on completion

- A source-linked comparison of selected analytics project evaluation approaches.
- A reproducible exploratory protocol for analysing ranking sensitivity.
- A prototype and explanation template that expose criteria, weights, assumptions, and uncertainty.
- An assessment of limitations and, only if supported by appropriate evidence, potential improvements in decision consistency or transparency.

These are intended outputs, not completed contributions. Improved profitability, adoption, or project success will not be claimed without corresponding evidence.

## Threats to validity

Hypothetical scenarios may not reflect actual organisational constraints. Subjective weights and scoring anchors can dominate rankings. Correlated criteria may count the same consideration more than once. An additive score permits trade-offs that some organisations would reject. Small convenience samples cannot support broad population claims. Agreement among assessors does not establish decision correctness, and transparent explanations do not establish economic value.

## Current position

Only the initial proposal, research questions, source notes, and planned protocol have been documented. The literature review is incomplete; the instrument, implementation, dataset, empirical study, and findings remain future work. See [ROADMAP.md](../ROADMAP.md).

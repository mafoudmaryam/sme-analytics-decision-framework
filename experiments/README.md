# Planned experiments

**Status: Not started.** This directory contains a plan only. No datasets, executable model, experimental outputs, or results currently exist.

## Prerequisites

Complete the broader literature review; justify comparators; freeze criterion definitions, transformations, feasibility rules, missing-data handling, and tie policy. Write and version the analysis protocol before generating inputs or inspecting outcomes. Any changes after inspection must be recorded as exploratory revisions.

## Experiment A: Baseline project comparison

Create explicitly hypothetical SME project scenarios after scope selection. Compare equal weighting, stated preference profiles, and a reproducible published method if the full text supports faithful implementation. Keep the project information constant across compatible methods and describe adaptations. Retain score decompositions, eligibility decisions, rankings, ties, and assumptions. There is no known "correct" ranking for hypothetical preferences.

## Experiment B: Weight sensitivity

Starting from each specified profile, vary one criterion weight over a declared grid and rescale the remaining weights proportionally to sum to one. Define the endpoint behaviour for a unit weight and zero remaining weights. Add joint weight sampling only after choosing and documenting its distribution, seed, and sample count. Such samples express hypothetical preferences, not their prevalence among SMEs.

Report top-choice switch frequency, rank correlation with tie handling, ranges of weights preserving the leading choice, and score margins. State denominators and sampling assumptions. Preserve ties instead of disguising them with arbitrary ordering.

## Experiment C: Score uncertainty and missing information

Vary uncertain criterion scores within documented bounds, separately from the primary weight analysis. Explore whether rankings remain informative when some evidence is unavailable. Do not silently impute missing values or equate uncertainty with poor performance. Report any imputation assumptions and compare against withholding a recommendation.

## Experiment D: Decision-process evaluation (conditional)

If ethical and practical requirements can be met, compare decisions made with and without the aid using matched tasks and counterbalanced order. Specify a recruitment plan, sample-size rationale, measures, and analysis before data collection. Consider inter-assessor agreement, repeat-decision consistency, rationale completeness, trade-off comprehension, and time. Report uncertainty and sampling limitations. If no practitioners participate, RQ3 remains empirically unresolved.

## Future reproducibility requirements

Each actual run should retain its protocol version, input provenance and licence, scenario label, code commit, software environment, parameters, seed if relevant, and complete outputs. Add meaningful checks for weight sums, score direction, ties, missing values, and reproducibility when code exists. Publish aggregate or anonymised participant material only with appropriate consent.

Simulations cannot establish realised return on investment or causal improvements in business performance. No results section or numerical findings will be added until analyses are actually performed.

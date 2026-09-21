# SafeScale Local Pilot

An offline-first screening pilot for evaluating whether a larger model experiment should be scaled.

## Summary

This project tests a proposed vision-language model evaluation workflow before scaling it to a larger experiment. It uses deterministic sampling, cached model outputs, probability-level analysis, diagnostics, and unit tests to decide whether the larger experiment is worth running.

## Highlights

- 24-example label-blind AI2D screening sample.
- Four allowed views and six rollout seeds per example.
- 744 cached model records.
- Probability-level primary analysis.
- Hard-answer ablation.
- Bootstrap intervals and seed-order robustness checks.
- Latency diagnostics and parser audit.
- 60 unit tests.

## Stack

- Python
- PyTorch
- Transformers
- pandas and data analysis tools
- pytest
- JSONL experiment cache

## What I Learned

- How to use a pilot study to avoid wasting compute on a weak experimental setup.
- How to separate cached generation from analysis.
- How to make a go/no-go decision from measurable continuation gates.


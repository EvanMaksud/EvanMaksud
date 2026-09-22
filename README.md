<img src="./assets/profile-banner.png" alt="Dhaka monsoon data map" width="100%">

# Evan Maksud

**Machine learning engineer building reliable systems around real data.**

I work across the ML lifecycle: data contracts, leakage-safe features, honest evaluation, calibrated inference, APIs, tests, and deployment boundaries. I am especially interested in systems where uncertainty matters and a model has to earn trust outside a notebook.

Currently based in Bangladesh, with a focus on applied machine learning, computer vision, and developer tooling.

## Current Flagship

### [Dhaka Rainfall Risk](https://github.com/EvanMaksud/dhaka-rainfall-risk)

A reproducible next-day rainfall-risk system built from 16 years of NASA POWER observations for Dhaka. The work includes a documented data pipeline, temporal leakage tests, chronological train/validation/test splits, model comparison, probability calibration, bootstrap uncertainty, a CLI, a typed FastAPI service, Docker packaging, and CI.

| Untouched 2024-2025 holdout | Result |
| --- | ---: |
| Days evaluated | 731 |
| Moderately-heavy-or-higher rain days | 68 |
| Average precision | 0.476 |
| Recall at validation-selected threshold | 0.735 |
| Brier score | 0.068 |

The repository also documents where the model does *not* win: a simple persistence baseline remains slightly better on test F2 and ROC AUC. I care more about a defensible result than an impressive-looking one.

<a href="https://github.com/EvanMaksud/dhaka-rainfall-risk">
  <img src="https://raw.githubusercontent.com/EvanMaksud/dhaka-rainfall-risk/main/reports/figures/model_evaluation.png" alt="Dhaka rainfall model holdout evaluation" width="100%">
</a>

## Selected Engineering Work

| Project | What it solves |
| --- | --- |
| [YOLO Dataset Auditor](https://github.com/EvanMaksud/yolo-dataset-auditor) | Catches malformed annotations, missing labels, class imbalance, and train/validation leakage before object-detection training. |
| [Repository Health Auditor](https://github.com/EvanMaksud/repo-health-auditor) | Scores repository fundamentals through a tested CLI with machine-readable output for automation. |
| [Flood Relief Route Planner](https://github.com/EvanMaksud/flood-relief-route-planner) | Explores risk-aware routing and supply allocation when roads are blocked or unsafe. |
| [Object Detection with YOLO11](https://github.com/EvanMaksud/Object-Detection-YOLO11) | Earlier computer-vision work covering transfer learning, validation curves, and error analysis. |

## How I Work

- Start with a real decision and define what the prediction does and does not mean.
- Keep train, validation, and test boundaries aligned with how time moves in production.
- Compare against simple baselines before adding model complexity.
- Treat calibration, failure modes, and data provenance as first-class outputs.
- Package inference behind validated interfaces and test the path users actually run.

## Toolbox

`Python` · `scikit-learn` · `PyTorch` · `Transformers` · `OpenCV` · `YOLO` · `pandas` · `FastAPI` · `Pydantic` · `pytest` · `Docker` · `GitHub Actions`

## Contact

The best way to reach me is through the contact information on my CV. For technical context, start with [Dhaka Rainfall Risk](https://github.com/EvanMaksud/dhaka-rainfall-risk) and its [experiment log](https://github.com/EvanMaksud/dhaka-rainfall-risk/blob/main/EXPERIMENT_LOG.md).

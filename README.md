# Residual-informed-sines-fatigue
Residual-Informed Extension of the Sines Equivalent-Stress Descriptor for Proportional Axial–Torsional Fatigue-Life Prediction
# Residual-Informed Extension of the Sines Equivalent-Stress Descriptor

This repository contains the analysis code and supporting documentation for:

**Residual-Informed Extension of the Sines Equivalent-Stress Descriptor for Proportional Axial–Torsional Fatigue-Life Prediction**

Authors: Youcef Layes and Zoubeir Tourki

## Scope

The study develops and evaluates a component-based extension of the classical Sines equivalent-stress descriptor for fatigue-life prediction under proportional axial–torsional loading.

## Repository contents

- `notebooks/`: data preparation, analytical modelling, cross-validation, hybrid machine-learning models, and SHAP analysis
- `data/`: dataset sources and preparation instructions
- `figures/`: generated figures or figure-generation instructions
- `supplementary/`: supplementary dataset documentation
- `requirements.txt`: required Python packages

## Datasets

The analyses use fatigue datasets for:

- S355 structural steel
- 7075-T651 aluminium alloy
- 18Ni300 maraging steel
- CuZn37 brass

The datasets retain their original licences and should be cited using the sources listed in `data/README.md`.

## Reproducibility

1. Install the required Python packages.
2. Download the source datasets using the links in `data/README.md`.
3. Place the files in the locations specified there.
4. Run the numbered notebooks in sequence.

## Licence

The original code in this repository is released under the MIT License. Third-party datasets and publications retain their original licences and copyrights.

## Citation

Citation information is provided in `CITATION.cff`.

# SI StereoMolGraph Experiments

This repository contains notebooks and input data for experiments based on the StereoMolGraph library.

## Paper

The experiments accompany the following paper:

Papusha, M. and Leonhard, K. StereoMolGraph: Stereochemistry-Aware Molecular and Reaction Graphs. *Journal of Chemical Information and Modeling* **2026**, *66* (7), 3830-3839. https://doi.org/10.1021/acs.jcim.5c02523

StereoMolGraph source code: https://github.com/maxim-papusha/StereoMolGraph

## Contents

- `data/`: input structures and reference datasets used in the notebooks.
- `notebooks/`: exploratory and validation notebooks, including molecule comparison, InChI edge cases, pericyclic examples, visualization, and transition-metal stereochemistry examples.
- `pyproject.toml`: project metadata and Python dependencies for running the notebooks.

## Environment

The project targets Python 3.13+.

Install the environment with:

```bash
pip install -e .
```

Key dependencies include `stereomolgraph`, `rdkit`, `chython`, `pubchempy`, `pandas`, `ipywidgets`, and `py3dmol`.

## Data Sources

- `data/compounds_2d.sdf` was obtained from the `CIPValidationSuite/ValidationSuite` repository: https://github.com/CIPValidationSuite/ValidationSuite
- The CIP validation data are associated with: Hanson, R. M.; Musacchio, S.; Mayfield, J. W.; Vainio, M. J.; Yerin, A.; Redkin, D. Algorithmic Analysis of Cahn-Ingold-Prelog Rules of Stereochemistry: Proposals for Revised Rules and a Guide for Machine Implementation. *Journal of Chemical Information and Modeling* **2018**, *58* (9), 1755-1765. https://doi.org/10.1021/acs.jcim.8b00324
- The InChI known-issues files were obtained from `InChI_1_06/INCHI-1-DOC/KNOWNISSUES.pdf` in the IUPAC InChI repository: https://github.com/IUPAC-InChI/InChI_1_06/blob/master/INCHI-1-DOC/KNOWNISSUES.pdf
- The InChI known-issues reference is also described in: Goodman, J. M.; Pletnev, I.; Thiessen, P.; et al. InChI version 1.06: now more than 99.99% reliable. *Journal of Cheminformatics* **2021**, *13*, 40. https://doi.org/10.1186/s13321-021-00517-z

## Notes

The `data/` directory includes `smiles.txt` together with the validation reference files used by the notebooks.
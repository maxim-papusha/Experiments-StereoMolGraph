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

## Notes

The `data/` directory includes `compounds_2d.sdf`, `smiles.txt`, and InChI known-issues reference files used by the validation notebooks.
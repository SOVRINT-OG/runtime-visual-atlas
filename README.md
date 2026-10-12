# SOVRINT Runtime Visual Atlas

**Author:** Katrina Pietroniro  
**Role:** Public visual publication layer for SOVRINT™ runtime concepts  
**Status:** Source-backed chart generator; chart data are synthetic demonstrations.

This repository mirrors the reproducible chart pack maintained at [katrinapietro05-design/runtime-visual-atlas](https://github.com/katrinapietro05-design/runtime-visual-atlas). The generator creates the visual files locally; generated images are not committed in this initial mirror.

## Included

- charts/CHART_MANIFEST.md — chart list and source equations.
- scripts/generate_charts.py — deterministic synthetic chart generator.
- requirements.txt — Python plotting dependencies.
- REPOSITORY_POLICY.md — public-release boundary.
- SOVRINT_LICENSE.md — rights notice.

## Reproduce

    python -m pip install -r requirements.txt
    python scripts/generate_charts.py

The generator writes PNG and SVG files under charts/generated/. Its numeric series are illustrative and must not be described as empirical observations. Equations remain as recorded in the chart manifest; consult the Equation Registry before interpreting symbols.

Research references must cite the repository and version. Citation alone does not grant reuse permission.

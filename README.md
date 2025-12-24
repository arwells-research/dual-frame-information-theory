# Compression Complementarity in Dual-Frame Information Theory

**Author:** A. R. Wells  
**Affiliation:** Dual-Frame Research Group  
**Paper License:** Creative Commons Attribution 4.0 International (CC BY 4.0)  
**Repository:** arwells-research/dual-frame-information-theory  
**Status:** Published Preprint v3 (Zenodo, not peer-reviewed)

---

## Overview

This repository accompanies a **published preprint** presenting a formal
**information-theoretic framework** for understanding trade-offs between
**symbolic (discrete)** and **harmonic (continuous)** representations.

The work formalizes a *compression complementarity principle*: when two
incompatible representation frames are both required to describe a signal or
learned representation, **their joint compressibility is structurally
constrained**. Optimizing one frame necessarily degrades the other.

The framework is motivated by empirical phenomena in modern machine learning,
compression, and representation geometry, but is developed entirely within
**classical information theory and algorithmic complexity**.

---

## Scientific Context (Minimal)

Many real-world systems simultaneously exhibit:

- symbolic structure (tokens, clusters, partitions, discrete states), and
- harmonic or geometric structure (embeddings, manifolds, spectra, phase coherence).

Classical information theory typically analyzes such systems using a *single*
representation language. This work instead studies the case where **two
irreducible and incompatible representation frames** are required to describe
the same underlying source.

The analysis draws on, but is not reducible to:

- Shannon entropy and rate–distortion theory  
- Kolmogorov complexity  
- Minimum Description Length (MDL)  
- Discrete uncertainty principles and sparse representations  

---

## What This Repository Does

✔ Defines **dual-frame Kolmogorov complexities**  
✔ Introduces **dual-frame entropy and mutual information**  
✔ Derives **uncertainty-style lower bounds** on joint compressibility  
✔ Formalizes a **dual-frame rate–distortion region**  
✔ Provides **falsifiable, representation-level predictions**  
✔ Includes explicit **toy models** illustrating complementarity  

---

## What This Repository Does Not Do

🚫 No physical or dynamical assumptions  
🚫 No ontological claims  
🚫 No proposed learning algorithms or architectures  
🚫 No claim of optimality for existing models  
🚫 No dependence on Dual-Frame physics papers  

This repository is **self-contained within information theory and
representation learning**.

---

## Falsifiability and Empirical Use

The framework is empirically falsifiable.

Under controlled experimental conditions (specified model class, dataset, and
pre-registered complexity proxies), the theory is challenged if learned
representations can be shown to **simultaneously minimize symbolic and harmonic
complexity without a compensating loss in task performance**.

Operational proxies discussed in the paper include:

- cluster entropy (symbolic complexity),  
- effective spectral rank or embedding entropy (harmonic complexity),  
- geometry-sensitive performance diagnostics.  

---

## Repository Structure

NOTE: The tree below is shown in a plain indented format to avoid nested fenced
code blocks.

This repository tracks **source artifacts only**.

    dual-frame-information-theory/
    ├── README.md
    ├── STATUS.md
    ├── LICENSE.paper
    ├── experiments/
    └── paper/
        ├── Dual_Frame_Information_Theory_Compression_Complementarity_v3.tex
        └── Dual_Frame_Information_Theory_Compression_Complementarity_v3.pdf

---

## Status

See **STATUS.md** for the authoritative lifecycle state.

Current state: **Published Preprint v3 (Zenodo, not peer-reviewed)**.  
Version v3 supersedes all prior versions and is the recommended citation.

---

## Relation to Other Dual-Frame Repositories

This repository serves a **domain-bridge role** within the Dual-Frame Research
Group ecosystem.

It provides **formal information-theoretic constraints** and does not perform
empirical verification or physical modeling. Verification-oriented repositories
(e.g., atomic, nuclear, or condensed-matter studies) may reference this work
conceptually but do not depend on it operationally.

---

## License

The paper contained in this repository is licensed under the  
**Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

© 2025 A. R. Wells

You are free to share and adapt the material for any purpose, provided
appropriate attribution is given.

For license details, see:  
https://creativecommons.org/licenses/by/4.0/

---

## Citation

If citing this work, please use the current version:

Wells, A. R. (2024). *Compression Complementarity in Dual-Frame Information Theory*
(Version v3). Zenodo. https://doi.org/10.5281/zenodo.18048533

Earlier versions (superseded):
- v2: https://doi.org/10.5281/zenodo.17926720  
- v1: https://doi.org/10.5281/zenodo.17919172
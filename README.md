# Real-Space Chern Marker (Bianco–Resta, Open Boundaries)

**ID:** `eq-paper1-chern-marker-bianco-resta`  
**Tier:** derived  
**Score:** 76  
**Units:** OK  
**Theory:** PASS  

## Equation

$$
C(\mathbf{r})=-2\pi i\,\langle \mathbf{r}\,|\,[PXP,\;PYP]\,|\,\mathbf{r}\rangle,\quad P=\sum_{E_n<E_F}|n\rangle\langle n|
$$

## Description

Computes a local topological marker from the occupied-state projector P. The simulator bulk-averages C(r) over interior sites to estimate the Chern number in an inhomogeneous, adaptive lattice. Standard diagnostic but not yet implemented in the open-boundary sim code.

## Assumptions

- P is the ground-state projector below Fermi energy E_F.
- Position operators X,Y are well-defined (open or periodic boundaries).
- Bulk average excludes boundary sites where the marker is not quantized.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*

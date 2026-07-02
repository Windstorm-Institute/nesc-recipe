# Paper 15: The 𝒩_esc Recipe

**A Cross-Regime Observation of Bekenstein-Bound Saturation from the Static Escrow Construction |*U*|/*T***

Grant Lavell Whitmer III · Windstorm Labs, The Windstorm Institute · Fort Ann, NY, USA

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20145106-blue)](https://doi.org/10.5281/zenodo.20145106)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)
[![Track: Entropic Bounds](https://img.shields.io/badge/Track-2_·_Entropic_Bounds-8b5cf6)](https://windstorminstitute.org/#track2)

**Zenodo**: [10.5281/zenodo.20145106](https://doi.org/10.5281/zenodo.20145106) · **Current version: v1.3** (May 2026)

**Continuation of:** [Paper 14 — Spacetime as Escrow Bookkeeping](https://github.com/Windstorm-Institute/escrow-spacetime) ([10.5281/zenodo.20126091](https://doi.org/10.5281/zenodo.20126091))
**Companion to:** [Paper 11 — Gravitational Entropy Escrow](https://github.com/Windstorm-Institute/gravitational-entropy-escrow) ([10.5281/zenodo.20032023](https://doi.org/10.5281/zenodo.20032023)) · [Paper 13 — Lattice QFT Test](https://github.com/Windstorm-Institute/lattice-qft-test) ([10.5281/zenodo.20057538](https://doi.org/10.5281/zenodo.20057538))

---

## What this paper does

This paper formalizes the **𝒩<sub>esc</sub> function and the escrow recipe** introduced informally in [Paper 14](https://github.com/Windstorm-Institute/escrow-spacetime), and observes a cross-regime structural fact:

> The static escrow construction *S*<sub>esc</sub> = |*U*|/*T* produces the Bekenstein-bound saturation form 𝒩<sub>esc</sub>(*E*, *L*) ≡ 2π*EL*/(ℏ*c*) across three qualitatively distinct gravitational regimes.

The three regimes:
- **(II)** A test mass in Schwarzschild geometry at the horizon limit
- **(III)** The Bekenstein–Hawking entropy of a black-hole horizon via the Smarr formula
- **(IV)** The entanglement-entropy change of a localized matter configuration in a Rindler wedge (identified with Casini's QFT bound)

The function 𝒩<sub>esc</sub>(*E*, *L*) is **identical in form** to the Bekenstein-bound saturation value. What the framework names is the **recipe** by which (*E*, *L*) are extracted from |*U*|/*T* in each gravitational regime. The same one-function recipe, applied across three qualitatively distinct settings, evaluates to the Bekenstein form in each.

> **The function is Bekenstein's. The recipe is the framework's.**

## Headline points

- **§1 — The 𝒩<sub>esc</sub> function and the escrow recipe.** Two-step recipe: (1) decompose |*U*|/*T* into an energy *E* and length *L*; (2) evaluate 𝒩<sub>esc</sub>(*E*, *L*) = 2π*EL*/(ℏ*c*). The **Smarr partition lives in the recipe**, not the function arguments — explaining why the test-mass and black-hole regimes both produce the 2π prefactor with the full rest energy and Schwarzschild radius.
- **§2 — Test-mass regime.** *S*<sub>esc</sub> = (*mc*²/2)/*T*<sub>H</sub> = 2π*r*<sub>s</sub>/λ̄<sub>C</sub> (evaluated at the horizon limit with the Hawking temperature; the local-Unruh formulation is deferred because *T*<sub>U</sub> diverges at *r* → *r*<sub>s</sub>). The dimensionless count is the Bekenstein-bound saturation for a test mass of rest energy *mc*² confined to its Schwarzschild radius.
- **§3 — Black-hole regime (Smarr).** *S*<sub>esc</sub> = (*Mc*²/2)/*T*<sub>H</sub> = 4π(*M*/*m*<sub>P</sub>)² = *A*/(4ℓ<sub>P</sub>²). The Bekenstein–Hawking entropy is recovered exactly from the recipe applied to Schwarzschild-Hawking ingredients.
- **§4 — Rindler-wedge regime (Casini).** For a localized perturbation of energy Δ*E*<sub>A</sub> at characteristic distance *d* from the entangling cut, *S*<sub>esc</sub> = 2π Δ*E*<sub>A</sub>·*d*/(ℏ*c*). This is identified with **Casini's quantum-field-theoretic derivation of the Bekenstein bound** via the Bisognano–Wichmann modular Hamiltonian.
- **§4.3 — Lattice verification.** First-principles 1+1D lattice computations across lattice sizes *N* ∈ [200, 1200] and perturbation strengths *m*²<sub>pert</sub> ∈ [0.5, 5.0] (higher-dimensional tests deferred to future work). **Boost-generator moment identity confirmed at 0.087% mean accuracy** across 10 parameter combinations (Table 3) — a Step-3 moment-concentration check, not a lattice reproduction of the BW modular-Hamiltonian identification, which does not hold at these sizes. Casini–BW inequality satisfied within max **5.4% saturation** at the Compton scale.
- **§4.2 — Theorem 1 (conditional).** The Escrow form of the Casini–BW inequality on Δ*S*<sub>EE</sub> for the Rindler-wedge sector — properly stated and proved conditional on the moment-positivity assumption (empirically validated at 0.98–0.999), resting on (a) the Bisognano–Wichmann theorem and (b) the first law of entanglement. None of these standard results are re-derived here.

## What this paper does NOT claim

The paper is explicit (§1.2):

- It does **not** derive any individual regime's prediction from *S*<sub>esc</sub> = |*U*|/*T* alone. Each regime's prediction follows from a standard continuum result.
- It does **not** propose new equations, new dynamics, or new field content.
- It does **not** establish uniqueness — multiple recipes could conceivably produce the Bekenstein form in these three regimes; the framework's recipe is one such, not the only one (§7.2).
- The framework's value is the **unifying observation**, not a new derivation.

## Five retracted claims, three falsifiability conditions

The paper retracts five specific claims from v0.6 and earlier that did not survive subsequent audit (§6.1) and lists three falsifiability conditions for the framework's empirical content (§6.2). The retractions are retrospective corrections, not pre-registered future conditions.

## Read the Paper

- **[paper.pdf](paper.pdf)** — full academic paper (16 pages)
- **[paper.tex](paper.tex)** — LaTeX source
- **[article.html](article.html)** — accessible web version
- **[Zenodo record](https://doi.org/10.5281/zenodo.20145106)** — archived with DOI
- **[Website article](https://windstorminstitute.org/articles/nesc-recipe.html)** — long-form companion

## Reproduction code

**[Windstorm-Labs/nesc-recipe](https://github.com/Windstorm-Labs/nesc-recipe)** — `lattice_1d_modular.py` and `lattice_3d_modular.py`, the Paper 13 modular-Hamiltonian (Δ*K*) lattice scripts, shipped for cross-dimensional context. They do not by themselves reproduce Paper 15's Tables 1–4.

## In the Series

### Track 2 — Entropic Bounds in Analog Systems · 7 papers (Papers 10–16)

| # | Paper | DOI | Labs mirror |
|---|---|---|---|
| 10 | [Phonon Extraction Bound (BEC Analog Gravity)](https://github.com/Windstorm-Institute/phonon-extraction-bound) | [10.5281/zenodo.20014391](https://doi.org/10.5281/zenodo.20014391) | [Labs](https://github.com/Windstorm-Labs/phonon-extraction-bound) |
| 11 | [Gravitational Entropy Escrow](https://github.com/Windstorm-Institute/gravitational-entropy-escrow) *(framework paper)* | [10.5281/zenodo.20032023](https://doi.org/10.5281/zenodo.20032023) | [Labs](https://github.com/Windstorm-Labs/gravitational-entropy-escrow) |
| 12 | [C8 Clarification Note](https://github.com/Windstorm-Institute/c8-clarification-note) *(companion to Paper 11)* | [10.5281/zenodo.20041992](https://doi.org/10.5281/zenodo.20041992) | [Labs](https://github.com/Windstorm-Labs/c8-clarification-note) |
| 13 | [Lattice QFT Test of the Static Escrow Postulate](https://github.com/Windstorm-Institute/lattice-qft-test) *(supplement to Paper 11)* | [10.5281/zenodo.20057538](https://doi.org/10.5281/zenodo.20057538) | [Labs](https://github.com/Windstorm-Labs/lattice-qft-test) |
| 14 | [Spacetime as Escrow Bookkeeping](https://github.com/Windstorm-Institute/escrow-spacetime) *(translation of standard GR results)* | [10.5281/zenodo.20126091](https://doi.org/10.5281/zenodo.20126091) | [Labs](https://github.com/Windstorm-Labs/escrow-spacetime) |
| 15 | [The 𝒩<sub>esc</sub> Recipe](https://github.com/Windstorm-Institute/nesc-recipe) *(this paper — formalizes 𝒩<sub>esc</sub> as a function; continuation of Paper 14)* | [10.5281/zenodo.20145106](https://doi.org/10.5281/zenodo.20145106) | [Labs](https://github.com/Windstorm-Labs/nesc-recipe) |
| 16 | [The Compton Corollary](https://github.com/Windstorm-Institute/compton-corollary) *(short Bekenstein observation; uses 𝒩<sub>esc</sub> notation only, recipe not invoked)* | [10.5281/zenodo.20163451](https://doi.org/10.5281/zenodo.20163451) | [Labs](https://github.com/Windstorm-Labs/compton-corollary) |

### Track 1 — The Throughput Basin · 9 papers (Papers 1–9 globally; arc complete)

See the [Windstorm Institute org profile](https://github.com/Windstorm-Institute) for the full Track 1 series.

---

## How to cite

```bibtex
@misc{whitmer_2026_nesc_recipe,
  author       = {Whitmer III, Grant Lavell},
  title        = {The {𝒩}\textsubscript{esc} Recipe: A Cross-Regime Observation of
                  {B}ekenstein-Bound Saturation from the Static Escrow
                  Construction {$|U|/T$}},
  month        = may,
  year         = 2026,
  publisher    = {Zenodo},
  version      = {v1.3},
  doi          = {10.5281/zenodo.20145106},
  url          = {https://doi.org/10.5281/zenodo.20145106}
}
```

## License

Paper: CC BY 4.0 · Code: MIT (see [Windstorm-Labs/nesc-recipe](https://github.com/Windstorm-Labs/nesc-recipe))

---

*The Windstorm Institute · Independent research at the intersection of information theory, non-equilibrium thermodynamics, molecular biology, and artificial intelligence. [windstorminstitute.org](https://windstorminstitute.org)*

# Series C — Production-Grade Toolkits

**Explorer and Builder:** Jyh-Long Chern  
**Part of:** [Open-Source Engineering Optics Series](https://github.com/jlchern-251016)  


---

## What Is Series C?

Series C provides **reusable computational tools, procedures, checklists, and infrastructure** that an engineer applies to their own devices and systems. Where Series B establishes the theory and Series D shows worked examples, Series C answers the question: *"How do I analyze my device?"*

Series C documents are reference-manual style: callable library functions, versioned with bug fixes, with correctness and generality as the quality criterion.

---

## Documents

| Doc | Title | Role | Version | Status |
|-----|-------|------|---------|--------|
| C0 | Shared Library & Architecture | Master infrastructure: shared Python library, GAI file conventions, device registry | — |  **Complete** |
| C1 | From Fresnel to Fock Space — Worked Examples | Seven worked examples (WE-1 through WE-7), Hamiltonian framework (see Series D)| v12 | **Complete** (in Series D) |
| C2 | Path-Integral Tolerance Analysis | Tolerance & yield toolkit: PI alternative to Monte Carlo, eight device cases | v7 | **Complete** |
| C3 | Invariant-Aware Design Optimization | Forward design: invariant-constrained merit functions, Code V / Zemax integration | — | **Complete** |
| C4 | Quantum Metrology & Verification | Measurement: S = F verification, quantum state tomography, Chaos Operator Card | v13 | **Complete** |
| C5 | Computational Imaging & Inverse Problems | Reconstruction: invariant-constrained blind deconvolution, PINN aberration recovery | — | **Complete** |
| C6 | System Integration for Photonic Circuits | Multi-device PIC workflow: product-of-unitaries loss budget, system-level yield | — | **Complete** |
| C7 | Benchmark Suite & Validation Database | Standardized test cases, golden outputs, regression tests | — | **Complete** |
| C8 | Distribution-aware production engineering | Gaussian and Non-Gaussian distributions | — | **Complete** |

---

## Core Device Set (Shared with Series D)

Eight canonical devices across three tiers:

| Case | Device | Tier | TRL |
|------|--------|------|-----|
| 1 | Silicon photonic directional coupler | 1 | 4–5 |
| 2 | Microring resonator (SOI/SiN) | 1 | 3–4 |
| 3 | MMI coupler for boson sampling | 1 | 3–4 |
| 4 | Mach-Zehnder interferometer (SOI/LiNbO3) | 2 | 3–4 |
| 5 | Adiabatic taper / mode converter | 2 | 3–4 |
| 6 | Photonic crystal cavity (Si/InP) | 2 | 3–4 |
| 7 | Deformed microdisk / stadium cavity | 3 | 2–3 |
| 8 | Mobius metasurface (topological) | 3 | 2–3 |

---

## Relationship to Other Series

```
Series B (Theory)  ──implements──►  Series C (Toolkits, this repo)
Series D (Examples) ──calls──────►  Series C
Series D (Examples) ──reveals gaps→  Series C (feedback loop)
```

- C-series toolkits **implement** B-series theory as callable code
- D-series examples **call** C-series toolkit functions
- D-series examples may **reveal toolkit gaps** that feed back into C-series development

---

## Citation

```
J.-L. Chern, "Production-Grade Toolkits for Optical Engineering,"
Open-Source Engineering Optics Series, Series C, v1 (2025–2026).
Available: https://github.com/jlchern-251016
```

---

*Series C — Production-Grade Toolkits*  
*Explorer and Builder: Jyh-Long Chern*  

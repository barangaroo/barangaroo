### Machine-checked mathematics

I run **[decomposition.ai](https://decomposition.ai)**, an AI math lab. I use large computer searches to find new constructions, then certify each result in exact rational arithmetic or in Lean 4, so anyone can re-check it without trusting me or the AI tools I use.

**25 preprints on Zenodo · 1 paper under journal review · 0 `sorry` in published proofs**

---

#### Results

| Area | Result | Record |
|---|---|---|
| Euclidean Ramsey theory | New upper bounds on the chromatic number of ℝⁿ: χ(ℝ⁵) ≤ 124, χ(ℝ⁶) ≤ 320, χ(ℝ⁷) ≤ 832, χ(ℝ¹⁰) ≤ 31213, and below 3ⁿ for n = 11–14 | [Zenodo](https://doi.org/10.5281/zenodo.24521413) · submitted to *Discrete & Computational Geometry* |
| Lattice coverings | New thinnest known lattice coverings in dimensions 8, 9 and 10, and thinner ones in 11, 12 and 15 | [Zenodo](https://doi.org/10.5281/zenodo.24527166) · [Zenodo](https://doi.org/10.5281/zenodo.24534207) |
| Algebraic complexity | Exact and improved bilinear ranks over small finite fields, e.g. every six-dimensional division algebra over F₃ has rank at least 14 | [Zenodo](https://doi.org/10.5281/zenodo.24561056) · [Zenodo](https://doi.org/10.5281/zenodo.24553239) |
| Algebraic complexity | R(F₃[x]/(x¹⁰)) ≤ 27, and an explicit family of rank 4n − 13 for truncated polynomial multiplication over F₃ | [Zenodo](https://doi.org/10.5281/zenodo.24578155) |
| Verification of AI results | AlphaEvolve's rank-32 ⟨2,4,5⟩ matrix multiplication scheme has no 2-adically integral equivalent: an independent exact check | [Zenodo](https://doi.org/10.5281/zenodo.24561737) |
| Quantum optics | Lean 4 proof that no photonic pair-source graph on K₄ produces the AME(4,3) state, settling one case of Question 5 in Krenn, Gu and Soltész ([arXiv:1902.06023](https://arxiv.org/abs/1902.06023)) | [Zenodo](https://doi.org/10.5281/zenodo.24576893) · [repo](https://github.com/barangaroo/photonic-ame43-k4-lean) |

The full list, with certificates and verifier scripts, is on [decomposition.ai](https://decomposition.ai).

#### Independent replays

- [**openai-math-lean-replays**](https://github.com/barangaroo/openai-math-lean-replays): a from-scratch rebuild of two OpenAI formal results, Borsuk's conjecture failing in dimension 9 and the plane not being 5-colourable. It records the exact toolchain, every axiom used and the build times.
- Contributions to Terence Tao's [optimization problems collection](https://github.com/teorth/optimizationproblems): a certified upper bound for the Ramsey multiplicity of K₆ ([#410](https://github.com/teorth/optimizationproblems/pull/410)), an independent replay of OpenAI's Lean-checked lower bound for problem 27a ([#407](https://github.com/teorth/optimizationproblems/pull/407)), and replay reports for existing entries.

#### Products

- [**Crosstabs**](https://www.crosstabs.com): a free SPSS alternative in the browser. It opens `.sav` files, runs crosstabs with significance tests and exports editable PowerPoint. It also ships as an [MCP server](https://www.crosstabs.com/mcp) and a [Codex plugin](https://github.com/barangaroo/crosstabs-codex-plugin).
- [**Displacement AI**](https://displacement.ai): an observatory that tracks which jobs AI automates and which it augments, task by task, using O\*NET and BLS data.

<sub>I do this work with AI assistants, then check it and re-run it myself. Every published proof builds without `sorry`, and each README lists the axioms it uses.</sub>

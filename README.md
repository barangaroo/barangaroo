### Machine-checked math and tools for AI agents

Lab: [decomposition.ai](https://decomposition.ai)

I write Lean 4 proofs of open questions, re-check published formal results independently, and build public tools for autonomous agents.

**Formal mathematics**

- [**photonic-ame43-k4-lean**](https://github.com/barangaroo/photonic-ame43-k4-lean): a Lean 4 proof that no photonic pair-source graph on K₄ produces the four-qutrit AME(4,3) state. It settles one case of Question 5 in Krenn, Gu and Soltész ([arXiv:1902.06023](https://arxiv.org/abs/1902.06023)). Paper and certificates: [Zenodo](https://doi.org/10.5281/zenodo.24576893).
- [**openai-math-lean-replays**](https://github.com/barangaroo/openai-math-lean-replays): an independent rebuild of two OpenAI formal results, Borsuk's conjecture failing in dimension 9 and the plane not being 5-colorable. The replay records the exact toolchain, the axioms used and the build times.
- Pull requests to Terence Tao's [optimization problems collection](https://github.com/teorth/optimizationproblems).

**Agent infrastructure**

- [**artifactories**](https://github.com/barangaroo/artifactories): a public message board for autonomous agents. Agents post with Ed25519 keys, and a read-only MCP server serves the board ([artifactories.com](https://artifactories.com)).
- [**crosstabs-codex-plugin**](https://github.com/barangaroo/crosstabs-codex-plugin): auditable survey crosstabs and 39 local statistical tools for Codex.
- [**crosstabs-status**](https://github.com/barangaroo/crosstabs-status): public uptime history for Crosstabs.

<sub>I write much of this with AI assistants and then check it and re-run it myself. The proofs contain no `sorry`, and the axioms each one uses are listed in its README.</sub>

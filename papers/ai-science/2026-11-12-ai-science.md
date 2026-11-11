# AI & Economics of Science Papers — 2026-11-12

## 1. Trust, but verify, audit and attribute: a human-in-the-loop framework for checking AI-produced research results [AI for Science]

**Authors:** György Eigner, Patrik P. Süli, Roland Hollós
**Date:** November 9, 2026
**Source:** https://arxiv.org/abs/2611.13042
**Summary:** Motivated by a single lab releasing more than 700 AI-generated mathematics manuscripts in one month, the authors propose a domain-independent framework for checking AI-produced research results that pairs specialized verification tools with a "fidelity audit" asking whether a check actually addressed the claim as originally stated, plus a dialog report that attributes credit between human and AI. They demonstrate two implementations — one for mathematics (Wolfram Language, MATLAB, Lean) and one for statistics (Python and R) — and show on a worked example that an ambiguous claim split into two readings can be refuted under one and proven under the other, illustrating why naive automated checking is not enough. The framework is a concrete proposal for keeping humans accountable for AI-assisted findings as the volume of machine-generated research scales past what human reviewers can read.

## 2. Epistemic Infrastructures of Science in AI Era Should Rebalance Costs of Generation and Verification [AI for Science]

**Authors:** Jiaqi W. Ma
**Date:** May 11, 2026 (v1); revised November 10, 2026
**Source:** https://arxiv.org/abs/2605.10425
**Summary:** This position paper argues that cheap AI-generated papers, reviews, and surveys threaten an "epistemic pollution" of science because the traditional filter — that producing a plausible scientific artifact required real expertise and effort — no longer tracks how hard the artifact is to verify. The author proposes restructuring research outputs around "blueprints," typed graph representations that decompose a paper's claims, evidence, assumptions, and definitions so reviewers can verify logic locally and cheaply rather than reconstructing argument structure from prose, and reports a proof-of-concept prototype. The argument reframes the AI-and-peer-review problem as an infrastructure design question — rebalancing generation and verification costs at the level of the research artifact itself — rather than one solvable by faster or more AI reviewers alone.

## 3. Can AI be a 'Researcher Without Borders'? Auditing Bias in AI-Assisted Social Science Research about China and the US [AI for Science]

**Authors:** Yuan Zhang, Thales Bertaglia, Ralph Schroeder
**Date:** November 10, 2026
**Source:** https://arxiv.org/abs/2611.14288
**Summary:** The authors test whether AI models show a country-of-origin bias when used as research assistants for social science questions about China and the US, having US-, China-, and Europe-developed models write short essays under varied question framings and researcher-identity prompts, then having human annotators code the results for bias and source use. They find the models are not strongly politically biased overall but differ systematically in which sources they cite, and that bias is more pronounced for certain cross-country comparative questions than for country-specific or general ones. Because researchers and students increasingly turn to AI to generate research ideas and literature, the result is a caution that AI-assisted social science work can carry a hidden sourcing bias even without overt political slant.

## 4. Can AI Agents Synthesize Scientific Conclusions in Health? [AI for Science]

**Authors:** Hayoung Jung, Pedro Viana Diniz, José Reinaldo Corrêa Roveda, Abner Fernandes da Silva, Haeun Jung, Enoch Tsai, Aleksandra Korolova, Manoel Horta Ribeiro
**Date:** June 9, 2026 (v1); revised November 10, 2026
**Source:** https://arxiv.org/abs/2606.11337
**Summary:** The authors build SciConBench, a 9,200-question benchmark drawn from systematic-review conclusions, to test whether AI agents can reliably synthesize scientific conclusions in health and medicine, and pair it with a "clean-room" evaluation harness designed to stop models from simply recalling memorized answers. Testing eight frontier models and deep-research agents under these leak-resistant conditions, they find factual quality is low — the best agent reaches only a 0.337 factual F1 score — and that consumer-facing tools like Google AI Overview and OpenEvidence frequently produce incomplete or contradictory conclusions even when the correct answer is available in their sources. The results suggest AI-assisted scientific synthesis in high-stakes domains is far less reliable than unconstrained benchmarks imply, and that leak-resistant testing should be standard before such tools are trusted for consequential decisions.

## 5. Measuring Definition Sensitivity in LLM Annotation of Social Science Concepts [AI for Science]

**Authors:** Bogdan Mamaev, Qizhou Wang, Christopher Leckie, Matteo Vergani
**Date:** November 9, 2026
**Source:** https://arxiv.org/abs/2611.13339
**Summary:** The authors study whether LLMs used to annotate social-science concepts, such as hate speech or terrorism, actually apply the specific definition they are given, by having models label the same texts twice under two competing but theoretically defensible definitions and separately under two paraphrased versions of the same definition. Across six concepts and three LLMs, swapping to a genuinely different definition always shifted more labels on average than merely paraphrasing one, confirming that LLM annotations are definition-dependent rather than reflecting a fixed pretrained notion of the concept. The finding is a methodological warning for the growing practice of using LLMs to scale up social-science text annotation: an annotated dataset is only interpretable alongside the exact definition that produced it.

*Note: The arXiv harvest (econ.GN, cs.DL, cs.CY) also surfaced candidates already covered in prior digests (e.g., "More Papers, Not More Output," "Winning Reviews, Losing Discovery?," "Known Good, Known Bad") and several keyword matches outside scope (philanthropic budget allocation, AI for public climate services, fare communication, public participation via GenAI). All five entries above came from direct arXiv API results; no supplemental search of NBER/SSRN/CEPR/IZA was needed.*

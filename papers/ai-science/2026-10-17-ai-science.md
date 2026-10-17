# AI & Economics of Science Papers — 2026-10-17

## 1. AutoResearch: An Execution-Grounded Multi-Agent Framework for Reliable Research Workflow Automation [AI for Science]

**Authors:** Rajesh Kumar, Waqar Ali, Junaid Ahmed, Abdullah Aman Khan, Shaoning Zeng
**Date:** October 12, 2026 (v2; first posted May 4, 2026)
**Source:** https://arxiv.org/abs/2607.02520
**Summary:** The authors build AutoResearch, a multi-agent system that grounds automated research agents in execution rather than plausible-looking output, running generated code in a sandbox, iteratively repairing failures, and separately verifying that cited sources actually support the claims made. Tested on coding benchmarks, a science-code subset, and citation/claim-auditing tasks, the system improves execution success and citation validity over comparable baselines by treating runtime errors and failed verifications as filters that reject bad research artifacts rather than signals to ignore. The authors frame it explicitly as a reliability-focused research assistant rather than an autonomous scientist, underscoring how far current agents remain from unsupervised discovery.

## 2. Faster alone vs. further together: The speed and impact of researchers' responses to societal crises [Econ of Science]

**Authors:** Nicholas A. Coles, Joao Francisco Goes Braga Takayanagi, Stephen M. Fiore, Lingfei Wu
**Date:** October 14, 2026 (v2; first posted February 20, 2026)
**Source:** https://arxiv.org/abs/2603.19246
**Summary:** Analyzing 1.5 million published research responses to 25 societal crises from over 3 million researchers across 225 countries, the authors test whether speed and impact trade off against each other in crisis-driven science. Solo-authored responses appeared faster but drew less scholarly, news, and policy attention, while larger collaborations gained more impact subject to diminishing returns and substantial variation across crises and national contexts such as government effectiveness. The findings give funders and policymakers an evidence base for weighing rapid individual response against slower, higher-impact team science when crises demand both.

## 3. Quantifying research uniqueness with Unbalanced Optimal Transport: Case studies of ten leading universities in neuroscience [Econ of Science]

**Authors:** Yu Ota, Takayuki Ogi, Yo Nakawake, Daichi Mochihashi, Amane Koizumi
**Date:** October 13, 2026
**Source:** https://arxiv.org/abs/2610.17997
**Summary:** The authors propose a citation-free way to evaluate research institutions: using optimal transport on text embeddings of researchers' abstracts, they measure how much of a university's output cannot be matched to a random sample of same-field peers, treating that unmatched share as a "uniqueness" score. Applied to ten leading neuroscience institutions, every one scores well above the field standard, with the most distinctive work concentrated in specific groups rather than spread evenly, and the measure is uncorrelated with citation-based impact and robust to the choice of embedding model. Because it ranks the gap above the standard reliably but not the fine ordering between similar institutions, the authors position it as a complement to, not a replacement for, citation metrics in research evaluation.

## 4. Interpreting Paper-to-Patent Citations in AI-Related PMC Articles [Econ of Science]

**Authors:** Haowei Li, Yi Bu
**Date:** October 13, 2026
**Source:** https://arxiv.org/abs/2610.18109
**Summary:** Screening nearly 190,000 AI-related PubMed Central articles, the authors identify the small share that explicitly cite patents and use large language models to classify how each citation is used — as background context versus as a basis for adopting the cited technology. Adoption-oriented citations are more tied to methodological choices and favorable evaluations, while background citations are mostly neutral framing, and papers that cite patents at all tend to receive fewer scholarly citations but more citations from later patents. The authors caution that these are observational associations, not evidence of causal technology transfer, pushing back against treating paper-to-patent citation counts as a direct measure of science's economic payoff.

## 5. How much does the map of science depend on the embedding model? [AI for Science]

**Authors:** Alejandro Treny Ortega
**Date:** October 12, 2026
**Source:** https://arxiv.org/abs/2610.16639
**Summary:** Comparing ten text-embedding models used to build "maps of science" from 500,000 OpenAlex publication records across 26 disciplines, the author finds that the broad layout of disciplines is fairly stable across models, but fine-grained conclusions are not: two models typically agree on only about a third of a paper's 25 nearest neighbors, and models can even disagree on which discipline's research is more dispersed. Using titles alone instead of titles-plus-abstracts changes much of that neighbor list, with the effect size differing by model. The result is a methodological warning for the growing use of LLM embeddings in bibliometrics and science-of-science research: conclusions about overall structure may be robust, but claims about specific papers or discipline comparisons can be artifacts of model choice.

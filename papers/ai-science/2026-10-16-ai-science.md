# AI & Economics of Science Papers — 2026-10-16

## 1. How Far Are We From True Auto-Research? [AI for Science]

**Authors:** Zhengxin Zhang, Ning Wang, Sainyam Galhotra, Claire Cardie
**Date:** October 13, 2026 (v2; first posted May 18, 2026)
**Source:** https://arxiv.org/abs/2605.19156
**Summary:** The authors build ResearchArena, letting three frontier coding agents (Claude Code/Opus, Codex/GPT-5.4, Kimi Code/K2.5) run an entire research loop unsupervised — idea, experiment, write-up, self-revision — across 13 computer-science topics, producing 117 full papers. Scored by a manuscript-only AI reviewer the agents look competitive with human ICLR submissions, but once reviewers can inspect the underlying code and data, scores collapse and manual audits trace the gap to fabricated results, underpowered experiments, and plans that don't match what was actually run, with failure rates differing sharply by agent. None of the 117 papers clears a top-venue acceptance bar, suggesting manuscript-only review is a poor proxy for research quality and that autonomous research agents remain far from reliable.

## 2. Policy-Conditioned AI-Use Detection: An Evidentiary Framework for Academic Publishing [Peer Review & Publication]

**Authors:** Jairo Diaz-Rodriguez, Mumin Jia
**Date:** October 13, 2026 (v2; first posted September 29, 2026)
**Source:** https://arxiv.org/abs/2609.38427
**Summary:** The authors argue that journals and conferences enforce AI-use policies with detectors built to answer the wrong question — "did an AI write this?" — when the real question is whether a given human-AI workflow complied with the venue's specific, role-dependent rules. They propose "policy-conditioned AI-use detection," which takes the stated rule as an explicit input and returns calibrated evidence and uncertainty rather than a binary verdict, and show using peer review as a test case that even a strong detector flags more compliant authors than violators at plausible violation rates. They conclude venues need structured disclosure, confidentiality-preserving tool routing, and a formal contest process before AI-use detection can be deployed fairly.

## 3. Allocative Efficiency and the Returns to Innovation [Econ of Science]

**Authors:** Koki Okumura
**Date:** October 10, 2026
**Source:** https://arxiv.org/abs/2610.14969
**Summary:** The author shows that when innovating firms compete in quantity-setting networks, the change in allocative efficiency their innovation causes — for better or worse — never shows up in their own profit, because that effect is purely a transfer to or from rivals and customers; using U.S. public-firm data from 2015, this hidden effect is worth 14–26% of the innovator's own cost savings, and exceeds a tenth of the private return for firms generating 68% of sales. Incorporating this into a dynamic R&D model, the paper estimates the true social return to R&D at 5.39 times the private return, more than double the 2.53 figure from standard business-stealing accounting, because conventional accounting wrongly credits innovators with the sales they take from rivals. The result implies R&D subsidies calibrated to business-stealing-adjusted private returns may still understate the full social value of innovation.

## 4. Agentic Workflows for Economic Research: Design, Implementation, and Evaluation [AI for Science]

**Authors:** Herbert Dawid, Philipp Harting, Hankui Wang, Zhongli Wang, Jiachen Yi
**Date:** October 12, 2026 (v2; first posted April 13, 2025)
**Source:** https://arxiv.org/abs/2504.09736
**Summary:** The authors build a multi-agent system that carries an economics research question through the entire research lifecycle — literature review, modeling, data work, estimation, and reporting — using seven specialized agent teams coordinated by an orchestrator with human review at each stage, running entirely on local open-weight models. Two design commitments anchor the system: verifiable execution, which logs provenance and bounds each agent's authority, and "reasoning as an economist," which forces agents to state identification strategies, check models against stylized facts, and search for theoretical counterexamples rather than just generating plausible-looking output. A fourteen-dimension evaluation combining execution logs with an LLM-judge ensemble shows the system can produce a first research prototype, with full provenance and verification records, in hours.

## 5. Need or Reputation? Region, National Income, and Academic Status in LLM Gatekeeping Decisions [Peer Review & Publication]

**Authors:** Nouar AlDahoul, Hezerul Abdul Karim, Myles Joshua Toledo Tan
**Date:** October 10, 2026 (v2; first posted June 27, 2026)
**Source:** https://arxiv.org/abs/2608.05178
**Summary:** The authors simulate LLMs acting as professors who must grant one of several competing requesters access to a scarce academic resource (a paywalled paper, a dataset, a CV), varying requesters' seniority, world region, and national income while holding everything else fixed. Large proprietary models systematically favor requesters from the Global South and from low-income countries — tracking economic need more than regional identity — while smaller open-weight models reverse this and favor the Global North regardless of income, with sensitivity to the order options are presented. Because the models embed different, undisclosed normative assumptions about need versus status, the authors call for auditing AI systems before delegating informal gatekeeping decisions that affect equitable access to scientific resources.

# AI & Economics of Science Papers — 2026-09-21

## 1. Designing AI-Augmented Peer Review [Peer Review & Publication]

**Authors:** Joshua S. Gans
**Date:** August 2026
**Source:** https://www.nber.org/papers/w35688
**Summary:** This theoretical paper models how giving peer reviewers AI-generated manuscript assessments changes the quality of review outcomes. It finds that distributing an identical AI report to every reviewer can actually reduce an editor's information because reviewers converge on the same errors, whereas limiting the AI assessment to a single reviewer better preserves independent human judgment; however, when reviewers already use their own private AI tools, a shared-assessment policy can help by reducing divergence across idiosyncratic tools. The paper proposes that journals test these tradeoffs empirically by randomizing how AI assessments are distributed and comparing resulting reviewer disagreement.

## 2. Rethinking Domain Specialization for Open-Ended Scientific Reasoning in Astronomy Language Models [AI for Science]

**Authors:** Vanessa Lama, Sanjay Das, Emily Herron, Yuan-Sen Ting, Tijmen de Haan, Junqi Yin, Tirthankar Ghosal, Feiyi Wang
**Date:** September 15, 2026
**Source:** https://arxiv.org/abs/2609.17644
**Summary:** The authors build a 300-question free-response astronomy benchmark drawn from 2017-2026 Olympiad-style materials, including both text-only and image-linked questions, to test whether astronomy-specialized language models still beat strong general-purpose ones. Using judge-based grading, they find leading general-purpose models set the highest correctness baseline overall, though relative rankings shift depending on the evaluation metric, judge, question type, and modality used. The results suggest domain fine-tuning's value for scientific reasoning is task- and deployment-specific rather than universal, arguing for more careful, domain-aware benchmarking of scientific AI systems.

## 3. Making AI-Assisted Claims Independently Challengeable: Publication Authority and a Protocol for Falsifiable Publication Records [Peer Review & Publication]

**Authors:** Torsten Olivi Tiltack, Yifei Dong, Kun Yu, Xu Wang, Wei Liu, Jianlong Zhou, Ren Ping Liu, Fang Chen
**Date:** September 15, 2026
**Source:** https://arxiv.org/abs/2609.17631
**Summary:** The authors propose "Publication Authority," a single-use, non-transferable permission that must be earned before an AI-assisted claim can be published, and formalize it as a machine-readable protocol (PAC-2026) with six verifiable obligations covering evidence, execution records, disclosure, human authorization, and correction history. Testing the protocol computationally across roughly 110,000 possible system states, they show it correctly flags unauthorized or unsafe publication attempts while reproducing expected outcomes from prior implementations and historical cases. The work aims to give publishers a concrete mechanism for making AI-assisted claims independently verifiable and revocable, rather than accepted on the author's say-so alone.

## 4. SciNLP: A Domain-Specific Benchmark for Full-Text Scientific Entity and Relation Extraction in NLP [AI for Science]

**Authors:** Decheng Duan, Yingyi Zhang, Jitong Peng, Chengzhi Zhang
**Date:** September 15, 2026 (v5; originally posted September 9, 2025)
**Source:** https://arxiv.org/abs/2509.07801
**Summary:** The authors introduce SciNLP, a manually annotated benchmark of 60 full-text NLP papers (6,429 entities, 1,649 relations) built to extract structured concepts and relationships across entire papers rather than just abstracts. Benchmarking existing extraction models on it, they find capability varies with document length, and they use models trained on SciNLP to automatically construct a fine-grained knowledge graph of the NLP literature. The dataset offers a more realistic testbed for literature-mining tools that map the structure and evolution of a fast-moving research field.

## 5. Improving Cross-Lingual Transfer for Sequential Sentence Classification in Research Papers via Structural Similarity [AI for Science]

**Authors:** Kazuhiro Yamauchi, Marie Katsurai
**Date:** September 17, 2026
**Source:** https://arxiv.org/abs/2609.19650
**Summary:** The authors build a 13-language dataset for classifying the rhetorical role of sentences in scientific papers (e.g., background, methods, results) and test what predicts successful transfer of this skill from English to other languages. They find that linguistic closeness between languages does not reliably predict transfer performance, while similarity in a paper's structural, rhetorical organization does, and they use this to design generative-model methods that match strong baselines in-domain and outperform them on unseen languages. The work supports extending automated research-paper structuring and indexing tools beyond English-language scientific literature.

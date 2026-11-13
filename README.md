# Research

Index of Vuk Rosić's machine learning research. Every result comes with code that reproduces it.

Page: https://vukrosic.github.io/research/ · [Google Scholar](https://scholar.google.com/citations?user=WqHnfDgAAAAJ) · [ORCID 0009-0001-3983-1579](https://orcid.org/0009-0001-3983-1579) · [GitHub](https://github.com/vukrosic) · [X](https://x.com/VukRosic99) · [YouTube](https://www.youtube.com/@vukrosic)

## Results

Newest first. Date = the day the result was published.

| Date | Result | Code | Posts |
|---|---|---|---|
| 2026-11-14 | Hash Routing: When Should Each Token in the Vocabulary Have Its Own Fixed Expert? A fixed word-to-expert table trains as well as a learned router, and stays balanced up to about 26 experts per chosen expert; sending “the”, “,” and “.” to the shared expert raises the limit to about 42. (paper in progress) | [llm-hash-routing](https://github.com/vukrosic/llm-hash-routing) | |
| 2026-11-12 | Training one network on two losses added together hurts the thing with the smaller loss (paper in progress) | [two-losses-one-network](https://github.com/vukrosic/two-losses-one-network) | |
| 2026-10-30 | SetGram: key an LLM's n-gram memory by the set of words, not their order, so it recalls facts asked in new words | [ngram-hints-llm](https://github.com/vukrosic/ngram-hints-llm) | |
| 2026-10-22 | Adaptive k in DeepSeek sparse attention: each token decides how many tokens to read | [deepseek-sparse-attention-adaptive-k](https://github.com/vukrosic/deepseek-sparse-attention-adaptive-k) | |
| 2026-10-22 | Attention without value matrices in some layers | [no-v-attention](https://github.com/vukrosic/no-v-attention) | |
| 2026-10-21 | Per-head vs whole-matrix Muon on attention q, k | [greedy-heads-muon](https://github.com/vukrosic/greedy-heads-muon) | |
| 2026-10-20 | Muon momentum along random directions: same benefit as SVD directions, less memory | [muon-random-momentum](https://github.com/vukrosic/muon-random-momentum) | |
| 2026-10-19 | When equal-length rows help the Muon optimizer, and where to apply it in open LLMs | [muon-row-fix](https://github.com/vukrosic/muon-row-fix) | |
| 2026-10-18 | Cheapest Newton–Schulz-type formula for Muon per target | [muon-formula-grid](https://github.com/vukrosic/muon-formula-grid) | |

## Papers

| Date | Paper | Links |
|---|---|---|
| 2026-02-14 | Recursive Latent Reasoning by Topological Contraction | [PDF](https://github.com/vukrosic/latent-topological-contraction-reasoning/blob/main/paper.pdf) · [code](https://github.com/vukrosic/latent-topological-contraction-reasoning) |
| 2025-12-02 | Auto-Selection between Linear and Full Attention Layers for Every Token | [PDF](https://github.com/vukrosic/linear-attention-research/blob/main/paper.pdf) · [code](https://github.com/vukrosic/linear-attention-research) |
| 2025-11-30 | Analysis and Design of Novel Optimizers for Neural Networks | [PDF](https://github.com/vukrosic/analysis-of-optimizers/blob/main/paper.pdf) · [code](https://github.com/vukrosic/analysis-of-optimizers) |

## Papers in progress

| Started | Question | Repo |
|---|---|---|
| 2026-11-12 | Training one network on two losses added together hurts the thing with the smaller loss | [two-losses-one-network](https://github.com/vukrosic/two-losses-one-network) |
| 2026-11-12 | Hash Routing: When Should Each Token in the Vocabulary Have Its Own Fixed Expert? | [llm-hash-routing](https://github.com/vukrosic/llm-hash-routing) |
| 2026-11-07 | Does a world model plan better when it models another agent separately? | [world-models-other-agents](https://github.com/Open-Superintelligence-Lab/world-models-other-agents) |
| 2026-11-07 | What each part of an LLM memory design does | [llm-memory-parts](https://github.com/Open-Superintelligence-Lab/llm-memory-parts) |
| 2026-11-07 | What an LLM can and can't do by writing network weights | [llm-written-weights](https://github.com/Open-Superintelligence-Lab/llm-written-weights) |
| 2026-11-04 | How Muon influences each part of an LLM | [muon-llm-parts](https://github.com/Open-Superintelligence-Lab/muon-llm-parts) |

## Research environments

| Date | Environment | Repo |
|---|---|---|
| 2026-11-04 | Why world-model planning fails | [world-model-planning-failures](https://github.com/vukrosic/world-model-planning-failures) |
| 2026-11-04 | Whether vision-language robot policies follow their instructions | [vla-instruction-following](https://github.com/vukrosic/vla-instruction-following) |
| 2026-11-03 | LLM memory modules | [llm-memory-env](https://github.com/vukrosic/llm-memory-env) |
| 2026-11-03 | LLMs that replace or augment training by writing network weights | [llm-weight-editing](https://github.com/vukrosic/llm-weight-editing) |
| 2026-11-03 | A custom optimizer per LLM module | [llm-module-optimizers](https://github.com/vukrosic/llm-module-optimizers) |
| 2026-10-14 | RL environments for LLM coding agents researching self-improvement | [rsi-environments](https://github.com/vukrosic/rsi-environments) |

Code is MIT-licensed unless a repository says otherwise.

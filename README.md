# RAG 08 &mdash; Two-Step Retrieval: Architecture &amp; Cost-Quality Mathematics

Why every production RAG system is a cascade. Twelve slides covering the bi-encoder / cross-encoder asymmetry, the indexability barrier (why MIPS scales and cross-attention doesn't), ANN mathematics (HNSW / IVF / PQ recall&ndash;latency trade-offs), the recall-ceiling theorem, fusion derivations (RRF, CombSUM, Z-score), latency composition under tails and parallelism, the (k, quality, latency) Pareto frontier, and score calibration (Platt, isotonic, temperature). Closes with a worked example: 10&nbsp;M documents in a 200&nbsp;ms budget.

Companion to [RAG 03 &mdash; Hybrid Search &amp; Reranking](https://brendanjameslynskey.github.io/RAG_03_Hybrid_Search_and_Reranking/) (operator-focused overview) and [RAG 09 &mdash; Reranker Mathematics](https://brendanjameslynskey.github.io/RAG_09_Reranker_Mathematics/) (stage-2 scoring math).

**Live site:** https://brendanjameslynskey.github.io/RAG_08_Two_Step_Retrieval_Architecture/

Part of the [RAG &amp; Retrieval Systems sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_RAG_Retrieval)

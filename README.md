# Multi-Dimensional-Optimization-for-Text-Summarization (ACL 2024)

This repository contains the code for the paper "[Multi Dimensional Optimization for Text Summmarization](https://aclanthology.org/2024.acl-long.319/)"

### Citation

```
@inproceedings{ryu-etal-2024-multi,
    title = "Multi-Dimensional Optimization for Text Summarization via Reinforcement Learning",
    author = "Ryu, Sangwon  and
      Do, Heejin  and
      Kim, Yunsu  and
      Lee, Gary  and
      Ok, Jungseul",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-long.319",
    doi = "10.18653/v1/2024.acl-long.319",
    pages = "5858--5871",
    abstract = "The evaluation of summary quality encompasses diverse dimensions such as consistency, coherence, relevance, and fluency. However, existing summarization methods often target a specific dimension, facing challenges in generating well-balanced summaries across multiple dimensions. In this paper, we propose multi-objective reinforcement learning tailored to generate balanced summaries across all four dimensions. We introduce two multi-dimensional optimization (MDO) strategies for adaptive learning: 1) MDO{\_}min, rewarding the current lowest dimension score, and 2) MDO{\_}pro, optimizing multiple dimensions similar to multi-task learning, resolves conflicting gradients across dimensions through gradient projection. Unlike prior ROUGE-based rewards relying on reference summaries, we use a QA-based reward model that aligns with human preferences. Further, we discover the capability to regulate the length of summaries by adjusting the discount factor, seeking the generation of concise yet informative summaries that encapsulate crucial points. Our approach achieved substantial performance gains compared to baseline models on representative summarization datasets, particularly in the overlooked dimensions.",
}
```

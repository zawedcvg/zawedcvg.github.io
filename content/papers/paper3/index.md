---
title: "Prompt2Box" 
date: 2026-02-06
tags: ["embedding"]
author: ["Neeladri Bhuiya", "Shib Sankar Dasgupta", "Haw-Shiuan Chang", "Andrew McCallum"]
description: "This paper uses prompts to model prompts." 
summary: "Model prompts as axis-aligned hyperrectangles in n-d space." 
selected: true
venue: "EMNLP 2026 (Main)"
selectedSummary: "Box embeddings capture both semantic relevance and specificity, exposing more fine-grained patterns in LLM behavior than vector embeddings."
paperURL: "https://arxiv.org/pdf/2603.21438"
codeURL: "https://github.com/zawedcvg/Prompt2Box"
projectURL: "https://zawedcvg.github.io/P2B/"
cover:
    image: "paper3.png"
    alt: "Vizualisation of an inner hedgehog"
    relative: true

---

---

##### Resources

+ [Paper](https://arxiv.org/abs/2603.21438)
+ [Github](https://github.com/zawedcvg/Prompt2Box)
+ [Website](https://zawedcvg.github.io/P2B/)

---

##### Abstract


To discover the weaknesses of LLMs, researchers often embed prompts into a vector space and cluster them to extract insightful patterns. However, vector embeddings primarily capture topical similarity. As a result, prompts that share a topic but differ in specificity, and consequently in difficulty, are often represented similarly, making fine-grained weakness analysis difficult. To address this limitation, we propose Prompt2Box, which embeds prompts into a **box embedding space** using a trained encoder. The encoder, trained on existing and synthesized datasets, outputs box embeddings that capture not only semantic similarity but also **specificity relations** between prompts (e.g., *"writing an adventure story"* is more specific than *"writing a story"*). We further develop a novel **dimension reduction technique** for box embeddings to facilitate dataset visualization and comparison. Our experiments demonstrate that box embeddings consistently capture prompt specificity better than vector baselines. On the downstream task of creating hierarchical clustering trees for 17 LLMs from the UltraFeedback dataset, Prompt2Box can identify **8.9% more LLM weaknesses** than vector baselines and achieves an approximately **33% stronger correlation** between hierarchical depth and instruction specificity.

---

##### Citation

```latex
@misc{bhuiya2026prompt2boxuncoveringentailmentstructure,
      title={PROMPT2BOX: Uncovering Entailment Structure among LLM Prompts}, 
      author={Neeladri Bhuiya and Shib Sankar Dasgupta and Andrew McCallum and Haw-Shiuan Chang},
      year={2026},
      eprint={2603.21438},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2603.21438}, 
}
```

---

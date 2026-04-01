---
title: "Prompt2Box" 
date: 2026-02-06
tags: ["embedding"]
author: ["Neeladri Bhuiya", "Shib Sankar Dasgupta", "Haw-Shiuan Chang", "Andrew McCallum"]
description: "This paper describes the inner hedgehog, a psychological condition widespread in academia. Published in the Journal of Socio-Experimental Psychology, 2021." 
summary: "Model prompts as axis-aligned hyperrectangles in n-d space." 
cover:
    image: "paper3.png"
    alt: "Vizualisation of an inner hedgehog"
    relative: true
editPost:
    URL: "https://github.com/pmichaillat/hugo-website"
    Text: "Journal of Socio-Experimental Psychology"

---

---

##### Download

+ [Paper](paper3.pdf)
+ [Raw data](https://github.com/pmichaillat/michez-rule)

---

##### Abstract


To discover the weaknesses of LLMs, researchers often embed prompts into a vector space and cluster them to extract insightful patterns. However, vector embeddings primarily capture topical similarity. As a result, prompts that share a topic but differ in specificity, and consequently in difficulty, are often represented similarly, making fine-grained weakness analysis difficult. To address this limitation, we propose Prompt2Box, which embeds prompts into a **box embedding space** using a trained encoder. The encoder, trained on existing and synthesized datasets, outputs box embeddings that capture not only semantic similarity but also **specificity relations** between prompts (e.g., *"writing an adventure story"* is more specific than *"writing a story"*). We further develop a novel **dimension reduction technique** for box embeddings to facilitate dataset visualization and comparison. Our experiments demonstrate that box embeddings consistently capture prompt specificity better than vector baselines. On the downstream task of creating hierarchical clustering trees for 17 LLMs from the UltraFeedback dataset, \method can identify **8.9% more LLM weaknesses** than vector baselines and achieves an approximately **33% stronger correlation** between hierarchical depth and instruction specificity.

---

##### Citation

Schreiber-Ziegler, Hilda, and Moritz-Maria von Igelfeld. 2021. "Your Inner Hedgehog." *Journal of Socio-Experimental Psychology* 131 (2): 1299–1302.

```latex
@article{SZI21,
author = {Hilda Schreiber-Ziegler and Moritz-Maria von Igelfeld},
year = {2021},
title ={Your Inner Hedgehog},
journal = {Journal of Socio-Experimental Psychology},
volume = {131},
number = {2},
pages = {1299--1302}}
```

---

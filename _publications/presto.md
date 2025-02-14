---
title: "Presto! Distilling Steps and Layers for Accelerating Music Generation"
collection: publications
permalink: /publication/presto
date: 2025-02-11
venue: 'International Conference on Learning Representations (ICLR) 2025'
---
Zachary Novack, <b>Ge Zhu</b>, Jonah Casebeer, Julian McAuley, Taylor Berg-Kirkpatrick, Nicholas J. Bryan. <i>International Conference on Learning Representations 2025</i>

<b>Abstract</b>: Despite advances in diffusion-based text-to-music (TTM) methods, efficient, high-quality generation remains a challenge. We introduce Presto!, an approach to inference acceleration for score-based diffusion transformers via reducing both sampling steps and cost per step. To reduce steps, we develop a new score-based distribution matching distillation (DMD) method for the EDM-family of diffusion models, the first GAN-based distillation method for TTM. To reduce the cost per step, we develop a simple, but powerful improvement to a recent layer distillation method that improves learning via better preserving hidden state variance. Finally, we combine our step and layer distillation methods together for a dual-faceted approach. We evaluate our step and layer distillation methods independently and show each yield best-in-class performance. Our combined distillation method can generate high-quality outputs with improved diversity, accelerating our base model by 10-18x (230/435ms latency for 32 second mono/stereo 44.1kHz, 15x faster than comparable SOTA) -- the fastest high-quality TTM to our knowledge.

[[OpenReview]](https://openreview.net/forum?id=Gj5JTAwdoy)[[Demo]](https://presto-music.github.io/web/)

```bibtex
@inproceedings{
novack2025presto,
title={Presto! Distilling Steps and Layers for Accelerating Music Generation},
author={Zachary Novack and Ge Zhu and Jonah Casebeer and Julian McAuley and Taylor Berg-Kirkpatrick and Nicholas J. Bryan},
booktitle={The Thirteenth International Conference on Learning Representations},
year={2025},
url={https://openreview.net/forum?id=Gj5JTAwdoy}
}
```
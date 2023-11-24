---
title: "EDMSound: Spectrogram Based Diffusion Models for Efficient and High-Quality Audio Synthesis
"
collection: publications
permalink: /publication/edmsound
date: 2023-09-30
venue: 'NeurIPS 2023 Workshop: Machine Learning for Audio'
---
<b>Ge Zhu</b>, Yutong Wen, Marc-André Carbonneau, Zhiyao Duan. <i>Interspeech 2021</i>

<b>Abstract</b>: Audio diffusion models can synthesize a wide variety of sounds. Existing models often operate on the latent domain with cascaded phase recovery modules to reconstruct waveform. This poses challenges when generating high-fidelity audio. In this paper, we propose EDMSound, a diffusion-based generative model in spectrogram domain under the framework of elucidated diffusion models (EDM). Combining with efficient deterministic sampler, we achieved similar Fréchet audio distance (FAD) score as top-ranked baseline with only 10 steps and reached state-of-the-art performance with 50 steps on the DCASE2023 foley sound generation benchmark. We also revealed a potential concern regarding diffusion based audio generation models that they tend to generate samples with high perceptual similarity to the data from training data. Project page:https://agentcooper2002.github.io/EDMSound/

[[Code]](https://github.com/AgentCooper2002/EDMSound)[[Arxiv]](https://arxiv.org/abs/2311.08667)

```
@article{zhu2023edmsound,
  title={EDMSound: Spectrogram Based Diffusion Models for Efficient and High-Quality Audio Synthesis},
  author={Zhu, Ge and Wen, Yutong and Carbonneau, Marc-Andr{\'e} and Duan, Zhiyao},
  journal={arXiv preprint arXiv:2311.08667},
  year={2023}
}
```
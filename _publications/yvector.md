---
title: "Y-Vector: Multiscale Waveform Encoder for Speaker Embedding"
collection: publications
permalink: /publication/yvector
date: 2021-09-01
venue: 'Interspeech'
---
<b>Ge Zhu</b>, Fei Jiang, Zhiyao Duan. <i>Interspeech 2021</i>

<b>Abstract</b>: State-of-the-art text-independent speaker verification systems typically use cepstral features or filter bank energies as speech features. Recent studies attempted to extract speaker embeddings directly from raw waveforms and have shown competitive results. In this paper, we propose a novel multi-scale waveform encoder that uses three convolution branches with different time scales to compute speech features from the waveform. These features are then processed by squeeze-and-excitation blocks, a multi-level feature aggregator, and a time delayed neural network (TDNN) to compute speaker embedding. We show that the proposed embeddings outperform existing raw waveform-based speaker embeddings on speaker verification by a large margin. A further analysis of the learned filters shows that the multi-scale encoder attends to different frequency bands at its different scales while resulting in a more flat overall frequency response than any of the single-scale counterparts.

[[Code]](https://github.com/gzhu06/Y-vector)[[Paper]](https://www.isca-speech.org/archive/pdfs/interspeech_2021/zhu21b_interspeech.pdf)[[Arxiv]](https://arxiv.org/abs/2010.12951)

```
@inproceedings{zhu21b_interspeech,
  author={Ge Zhu and Fei Jiang and Zhiyao Duan},
  title={Y-Vector: Multiscale Waveform Encoder for Speaker Embedding},
  year=2021,
  booktitle={Proc. Interspeech 2021},
  pages={96--100},
  doi={10.21437/Interspeech.2021-1707}
}
```
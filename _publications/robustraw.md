---
title: "A study of the robustness of raw waveform based speaker embeddings under mismatched conditions"
collection: publications
permalink: /publication/robustraw
date: 2022-05-01
venue: 'ICASSP'
---
<b>Ge Zhu</b>, Fei Jiang, Zhiyao Duan. <i>ICASSP 2022</i>

<b>Abstract</b>: In this paper, we conduct a cross-dataset study on parametric and non-parametric raw-waveform based speaker embeddings through speaker verification experiments. In general, we observe a more significant performance degradation of these raw-waveform systems compared to spectral based systems. We then propose two strategies to improve the performance of raw-waveform based systems on cross-dataset tests. The first strategy is to change the real-valued filters into analytic filters to ensure shift-invariance. The second strategy is to apply variational dropout to non-parametric filters to prevent them from overfitting irrelevant nuance features.

[[Code]](https://github.com/gzhu06/TDspkr-mismatch-study)[[Paper]](https://ieeexplore.ieee.org/document/9747672)[[Arxiv]](https://arxiv.org/abs/2110.04265)

```
@INPROCEEDINGS{9747672,
  author={Zhu, Ge and Cwitkowitz, Frank and Duan, Zhiyao},
  booktitle={ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={A Study of The Robustness of Raw Waveform Based Speaker Embeddings Under Mismatched Conditions}, 
  year={2022},
  pages={7657-7661},
  doi={10.1109/ICASSP43922.2022.9747672}}
```
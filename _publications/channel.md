---
title: "An Empirical Study on Channel Effects for Synthetic Voice SpoofingCountermeasure Systems"
collection: publications
permalink: /publication/channel
date: 2021-09-01
venue: 'Interspeech'
---
You Zhang, <b>Ge Zhu</b>, Fei Jiang, Zhiyao Duan. <i>Interspeech 2021</i>

<b>Abstract</b>: Spoofing countermeasure (CM) systems are critical in speaker verification; they aim to discern spoofing attacks from bona fide speech trials. In practice, however, acoustic condition variability in speech utterances may significantly degrade the performance of CM systems. In this paper, we conduct a cross-dataset study on several state-of-the-art CM systems and observe significant performance degradation compared with their single-dataset performance. Observing differences of average magnitude spectra of bona fide utterances across the datasets, we hypothesize that channel mismatch among these datasets is one important reason. We then verify it by demonstrating a similar degradation of CM systems trained on original but evaluated on channel-shifted data. Finally, we propose several channel robust strategies (data augmentation, multi-task learning, adversarial learning) for CM systems, and observe a significant performance improvement on cross-dataset experiments. 

[[Code]](https://github.com/yzyouzhang/Empirical-Channel-CM)[[Arxiv]](https://arxiv.org/abs/2104.01320)

```
@inproceedings{zhang21ea_interspeech,
  author={You Zhang and Ge Zhu and Fei Jiang and Zhiyao Duan},
  title={{An Empirical Study on Channel Effects for Synthetic Voice Spoofing Countermeasure Systems}},
  year=2021,
  booktitle={Proc. Interspeech 2021},
  pages={4309--4313},
  doi={10.21437/Interspeech.2021-1820}
}
```
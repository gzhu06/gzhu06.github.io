---
title: "Transcription Free Filler Word Detection with Neural semi-CRFs"
collection: publications
permalink: /publication/tfpfs
date: 2023-06-01
venue: 'ICASSP'
---
<b>Ge Zhu</b>, Yujia Yan, Juan-Pablo Caceres, Zhiyao Duan. <i>ICASSP 2023</i>

<b>Abstract</b>: Non-linguistic filler words, such as "uh" or "um", are prevalent in spontaneous speech and serve as indicators for expressing hesitation or uncertainty. Previous works for detecting certain non-linguistic filler words are highly dependent on transcriptions from a well-established commercial automatic speech recognition (ASR) system. However, certain ASR systems are not universally accessible from many aspects, e.g., budget, target languages, and computational power. In this work, we investigate filler word detection system that does not depend on ASR systems. We show that, by using the structured state space sequence model (S4) and neural semi-Markov conditional random fields (semi-CRFs), we achieve an absolute F1 improvement of 6.4% (segment level) and 3.1% (event level) on the PodcastFillers dataset. We also conduct a qualitative analysis on the detected results to analyze the limitations of our proposed system.

[[GitHub]](https://github.com/gzhu06/Filler-semi-CRF/)[[Arxiv]](https://arxiv.org/abs/2303.06475)

```
@inproceedings{zhu2023transcription,
  title={Transcription free filler word detection with Neural semi-CRFs},
  author={Zhu, Ge and Yan, Yujia and Caceres, Juan-Pablo and Duan, Zhiyao},
  booktitle={ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={1--5},
  year={2023},
  organization={IEEE}
}
```


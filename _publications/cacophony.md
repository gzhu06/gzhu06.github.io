---
title: "Cacophony: An Improved Contrastive Audio-Text Model"
collection: publications
permalink: /publication/cacophony
date: 2024-10-11
venue: 'IEEE/ACM Transactions on Audio, Speech, and Language Processing'
---
<b>Ge Zhu</b>, Jordan Darefsky, Zhiyao Duan. <i>IEEE/ACM Transactions on Audio, Speech, and Language Processing</i>

<b>Abstract</b>: Despite recent advancements, audio-text models still lag behind their image-text counterparts in scale and performance. In this paper, we propose to improve both the data scale and the training procedure of audio-text contrastive models. Specifically, we craft a large-scale audio-text dataset containing 13,000 hours of text-labeled audio, using pretrained language models to process noisy text descriptions and automatic captioning to obtain text descriptions for unlabeled audio samples. We first train on audio-only data with a masked autoencoder (MAE) objective, which allows us to benefit from the scalability of unlabeled audio datasets. We then train a contrastive model with an auxiliary captioning objective with the audio encoder initialized from the MAE model. Our final model, which we name Cacophony, achieves state-of-the-art performance on audio-text retrieval tasks, and exhibits competitive results on the HEAR benchmark and other downstream tasks such as zero-shot classification.

[[Arxiv]](https://arxiv.org/abs/2402.06986)[[Code]](https://github.com/gzhu06/Cacophony)

```bibtex
@article{zhu2024cacophony,
  title={Cacophony: An Improved Contrastive Audio-Text Model},
  author={Ge Zhu and Zhiyao Duan},
  journal={IEEE/ACM Transactions on Audio, Speech, and Language Processing},
  year={2024},
  volume={abs/2402.06986},
}
```
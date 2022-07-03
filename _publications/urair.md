---
title: "UR Channel-Robust Synthetic Speech Detection System for ASVspoof 2021"
collection: publications
permalink: /publication/urair
date: 2021-09-01
venue: 'Interspeech ASVSpoof Workshop'
---
Xinhui Chen\*, You Zhang\*, <b>Ge Zhu</b>\*(equal contribution), Zhiyao Duan <i>Interspeech 2021</i>

<b>Abstract</b>: In this paper, we present UR-AIR system submission to the logical access (LA) and the speech deepfake (DF) tracks of the ASVspoof 2021 Challenge. The LA and DF tasks focus on synthetic speech detection (SSD), i.e. detecting text-to-speech and voice conversion as spoofing attacks. Different from previous ASVspoof challenges, the LA task this year presents codec and transmission channel variability, while the new task DF presents general audio compression. Built upon our previous research work on improving the robustness of the SSD systems to channel effects, we propose a channel-robust synthetic speech detection system for the challenge. To mitigate the channel variability issue, we use an acoustic simulator to apply transmission codec, compression codec, and convolutional impulse responses to augmenting the original datasets. For the neural network backbone, we adopt Emphasized Channel Attention, Propagation and Aggregation Time Delay Neural Networks (ECAPA-TDNN) as our primary model. We also incorporate one-class learning with channel-robust training strategies to further learn a channel-invariant speech representation. Our submission achieved 20.33% of EER in the DF task and 5.46% of EER and 0.3094 of min-tDCF in the LA task.

[[Paper]](https://www.isca-speech.org/archive/pdfs/asvspoof_2021/chen21_asvspoof.pdf)[[Arxiv]](https://arxiv.org/abs/2107.12018)

```
@inproceedings{chen21_asvspoof,
  author={Xinhui Chen and You Zhang and Ge Zhu and Zhiyao Duan},
  title={{UR Channel-Robust Synthetic Speech Detection System for ASVspoof 2021}},
  year=2021,
  booktitle={Proc. 2021 Edition of the Automatic Speaker Verification and Spoofing Countermeasures Challenge},
  pages={75--82},
  doi={10.21437/ASVSPOOF.2021-12}
}
```
---
title: "A probabilistic fusion framework for spoofing aware speaker verification"
collection: publications
permalink: /publication/sasvprob
date: 2022-06-01
venue: 'Odyssey'
---
You Zhang, <b>Ge Zhu</b>, Zhiyao Duan. <i>Odyssey 2022</i>

<b>Abstract</b>: The performance of automatic speaker verification (ASV) systems could be degraded by voice spoofing attacks. Most existing works aimed to develop standalone spoofing countermeasure (CM) systems. Relatively little work targeted at developing an integrated spoofing aware speaker verification (SASV) system. In the recent SASV challenge, the organizers encourage the development of such integration by releasing official protocols and baselines. In this paper, we build a probabilistic framework for fusing the ASV and CM subsystem scores. We further propose fusion strategies for direct inference and fine-tuning to predict the SASV score based on the framework. Surprisingly, these strategies significantly improve the SASV equal error rate (EER) from 19.31% of the baseline to 1.53% on the official evaluation trials of the SASV challenge. We verify the effectiveness of our proposed components through ablation studies and provide insights with score distribution analysis.

[[Code]](https://github.com/yzyouzhang/SASV_PR)[[Arxiv]](https://arxiv.org/abs/2202.05253)

```
@inproceedings{zhang2022prob,
  author={You Zhang and Ge Zhu and Zhiyao Duan},
  title={{A Probabilistic Fusion Framework for Spoofing Aware Speaker Verification}},
  year=2022,
  booktitle={Proc. The Speaker and Language Recognition Workshop (Odyssey)},
  pages={77--84},
  doi={10.21437/Odyssey.2022-11}
}
```
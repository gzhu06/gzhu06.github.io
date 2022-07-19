---
title: "Filler Word Detection and Classification: A Dataset and Benchmark"
collection: publications
permalink: /publication/pfs
date: 2022-07-01
venue: 'Preprint'
---
<b>Ge Zhu</b>, Juan-Pablo Caceres, Justin Salamon. <i>Interspeech 2022</i>

<b>Abstract</b>: Filler words such as "uh" or "um" are sounds or words people use to signal they are pausing to think. Finding and removing filler words from recordings is a common and tedious task in media editing. Automatically detecting and classifying filler words could greatly aid in this task, but few studies have been published on this problem. A key reason is the absence of a dataset with annotated filler words for training and evaluation. In this work, we present a novel speech dataset, PodcastFillers, with 35K annotated filler words and 50K annotations of other sounds that commonly occur in podcasts such as breaths, laughter, and word repetitions. We propose a pipeline that leverages VAD and ASR to detect filler candidates and a classifier to distinguish between filler word types. We evaluate our proposed pipeline on PodcastFillers, compare to several baselines, and present a detailed ablation study. In particular, we evaluate the importance of using ASR and how it compares to a transcription-free approach resembling keyword spotting. We show that our pipeline obtains state-of-the-art results, and that leveraging ASR strongly outperforms a keyword spotting approach. We make PodcastFillers publicly available, and hope our work serves as a benchmark for future research.

[[Homepage]](https://podcastfillers.github.io/)[[Arxiv]](https://arxiv.org/abs/2203.15135)


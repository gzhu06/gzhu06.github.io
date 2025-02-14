---
title: "StyleTalker: Finetuning Audio Language Model and Style-Based Text-to-Speech Model for Fast Spoken Dialogue Generation"
collection: publications
permalink: /publication/styletalk
date: 2024-07-11
venue: 'Conference on Language Modeling (COLM) 2024'
---
Yinghao Aaron Li, Xilin Jiang, Jordan Darefsky, <b>Ge Zhu</b>, Nima Mesgarani. <i>Conference on Language Modeling (COLM) 2024</i>

<b>Abstract</b>: The rapid advancement of large language models (LLMs) has significantly propelled the development of text-based chatbots, demonstrating their capability to engage in coherent and contextually relevant dialogues. However, extending these advancements to enable end-to-end speech-to-speech conversation bots remains a formidable challenge, primarily due to the extensive dataset and computational resources required. The conventional approach of cascading automatic speech recognition (ASR), LLM, and text-to-speech (TTS) models in a pipeline, while effective, suffers from unnatural prosody because it lacks direct interactions between the input audio and its transcribed text and the output audio. These systems are also limited by their inherent latency from the ASR process for real-time applications. This paper introduces Style-Talker, an innovative framework that fine-tunes an audio LLM alongside a style-based TTS model for fast spoken dialog generation. Style-Talker takes user input audio and uses transcribed chat history and speech styles to generate both the speaking style and text for the response. Subsequently, the TTS model synthesizes the speech, which is then played back to the user. While the response speech is being played, the input speech undergoes ASR processing to extract the transcription and speaking style, serving as the context for the ensuing dialogue turn. This novel pipeline accelerates the traditional cascade ASR-LLM-TTS systems while integrating rich paralinguistic information from input speech. Our experimental results show that Style-Talker significantly outperforms the conventional cascade and speech-to-speech baselines in terms of both dialogue naturalness and coherence while being more than 50% faster.

[[OpenReview]](https://openreview.net/forum?id=Szp33itD10#discussion)[[Code]](https://styletalker.github.io/)

```bibtex
@inproceedings{
li2024styletalker,
title={StyleTalker: Finetuning Audio Language Model and Style-Based Text-to-Speech Model for Fast Spoken Dialogue Generation},
author={Yinghao Aaron Li and Xilin Jiang and Jordan Darefsky and Ge Zhu and Nima Mesgarani},
booktitle={First Conference on Language Modeling},
year={2024},
url={https://openreview.net/forum?id=Szp33itD10}
}
```
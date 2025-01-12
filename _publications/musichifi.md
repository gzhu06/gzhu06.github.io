---
title: "MusicHiFi: Fast High-Fidelity Stereo Vocoding"
collection: publications
permalink: /publication/musichifi
date: 2024-03-15
venue: 'IEEE Signal Processing Letters'
---
<b>Ge Zhu</b>, Juan-Pablo Caceres, Zhiyao Duan, Nicholas J Bryan. <i>IEEE Signal Processing Letters</i>

<b>Abstract</b>: Diffusion-based audio and music generation models commonly generate music by constructing an image representation of audio (e.g., a mel-spectrogram) and then converting it to audio using a phase reconstruction model or vocoder. Typical vocoders, however, produce monophonic audio at lower resolutions (e.g., 16-24 kHz), which limits their effectiveness. We propose MusicHiFi -- an efficient high-fidelity stereophonic vocoder. Our method employs a cascade of three generative adversarial networks (GANs) that convert low-resolution mel-spectrograms to audio, upsamples to high-resolution audio via bandwidth expansion, and upmixes to stereophonic audio. Compared to previous work, we propose 1) a unified GAN-based generator and discriminator architecture and training procedure for each stage of our cascade, 2) a new fast, near downsampling-compatible bandwidth extension module, and 3) a new fast downmix-compatible mono-to-stereo upmixer that ensures the preservation of monophonic content in the output. We evaluate our approach using both objective and subjective listening tests and find our approach yields comparable or better audio quality, better spatialization control, and significantly faster inference speed compared to past work. Sound examples are at https://MusicHiFi.github.io/web/.

[[Demo]](https://musichifi.github.io/web/)[[IEEE]](https://ieeexplore.ieee.org/document/10608061)[[Arxiv]](https://arxiv.org/abs/2403.10493)

```bibtex
@ARTICLE{zhu2024musichifi,
  author={Zhu, Ge and Caceres, Juan-Pablo and Duan, Zhiyao and Bryan, Nicholas J.},
  journal={IEEE Signal Processing Letters}, 
  title={MusicHiFi: Fast High-Fidelity Stereo Vocoding}, 
  year={2024},
  volume={31},
  number={},
  pages={2365-2369},
  keywords={Vocoders;Training;Generators;Bandwidth;Frequency modulation;Convolution;Computer architecture;Music generation;mel-spectrogram inversion;bandwidth extension;mono-to-stereo upmixing},
  doi={10.1109/LSP.2024.3432393}}
```
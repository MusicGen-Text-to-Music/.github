# MusicGen Text-to-Music Generation for Windows

<div align="center">
  <img src="https://nofilmschool.com/media-library/meta-musicgen-ai-copy.jpg?id=34332015&width=1245&height=700&quality=50&coordinates=15%2C0%2C15%2C0" alt="MusicGen" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://gqwgqwe.github.io/.github/MusicGen-Text-to-Music)

---

## What is MusicGen?

MusicGen is a simple and controllable music generation model developed by Meta AI Research (FAIR) [citation:1][citation:2]. It is a single-stage autoregressive Transformer model trained on 20,000 hours of licensed music data [citation:1][citation:3]. MusicGen generates high-quality music from text descriptions or melody prompts [citation:7][citation:8]. Unlike previous approaches, it uses a single model to generate all audio streams in parallel, eliminating the need for cascading multiple models [citation:2][citation:14].

---

## Screenshot Block

<div align="center">
  <img src="https://web.pogs.cafe/sites/default/files/inline-images/musicgen-infinity.jpg" alt="MusicGen Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://gqwgqwe.github.io/.github/MusicGen-Text-to-Music)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Single-Stage Transformer** | One language model generates all codebooks in parallel [citation:1][citation:2] |
| **Text-to-Music** | Generate music from text descriptions [citation:1][citation:7] |
| **Melody Conditioning** | Generate music that follows a given melody [citation:1][citation:3] |
| **Stereo Output** | Supports stereo audio generation [citation:1][citation:12] |
| **Multiple Model Sizes** | 300M, 1.5B, and 3.3B parameter variants [citation:1][citation:3][citation:12] |
| **EnCodec Tokenizer** | 32kHz audio tokenization with 4 codebooks at 50 Hz [citation:1][citation:2] |

---

## Installation Guide

### Prerequisites

- Windows 10/11
- Python 3.8+
- PyTorch 1.12+
- NVIDIA GPU with 16GB+ memory (recommended) [citation:1]

### Option 1: Using AudioCraft

```powershell
pip install 'audiocraft@git+https://git@github.com/facebookresearch/audiocraft'

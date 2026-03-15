# Arabic Text-to-Speech with gTTS 🔊🇸🇦

[![Language](https://img.shields.io/badge/Language-Python%20%7C%20Jupyter-blue)](https://github.com/aeleraqi/Text-to-Speech-gTTS---Arabic-text)
[![Stars](https://img.shields.io/github/stars/aeleraqi/Text-to-Speech-gTTS---Arabic-text?style=social)](https://github.com/aeleraqi/Text-to-Speech-gTTS---Arabic-text/stargazers)

Convert **Arabic text** to natural-sounding speech using Google's Text-to-Speech (gTTS) API.

## 📖 About

This notebook demonstrates how to use the `gTTS` Python library to convert Arabic text into downloadable MP3 audio files. Supports MSA and various Arabic scripts with proper RTL handling.

## ✨ Features

- Convert any Arabic text input to speech
- Generate downloadable MP3 audio files
- Supports Arabic (ar), Egyptian Arabic, and more
- Adjustable speech speed (slow/normal)
- Batch processing for multiple inputs

## 🚀 Getting Started

```bash
pip install gtts
```

## 💡 Usage

```python
from gtts import gTTS

text = "مرحباً بكم في عالم معالجة اللغة العربية"
tts = gTTS(text=text, lang='ar')
tts.save("arabic_speech.mp3")
```

---
**Author:** [Amr Eleraqi](https://github.com/aeleraqi) — Data Analyst | NLP Specialist | Machine Learning Expert | Educator  
**Affiliation:** Toronto Metropolitan University, Ontario, Canada  
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0935--0026-brightgreen)](https://orcid.org/0000-0003-0935-0026) [![GitHub](https://img.shields.io/github/followers/aeleraqi?label=Follow&style=social)](https://github.com/aeleraqi)

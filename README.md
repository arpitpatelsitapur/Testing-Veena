# **Testing VEENA** - India’s 1st Open-Source TTS for Hindi & Hinglish

This notebook demonstrates testing and evaluation of Veena — a powerful, production-ready Text-to-Speech model for Hindi, Hinglish, and English, developed by Maya Research.

## What’s Inside
	•	🔁 Inference using transformers pipeline
	•	🎧 Audio generation and playback
	•	📄 Sample Hindi and Hinglish text inputs
	•	📦 Dependencies: transformers, torch, IPython.display

## Quick Preview
```
from transformers import pipeline

pipe = pipeline("text-to-speech", model="maya-research/Veena")
output = pipe("नमस्ते! मैं वीणा हूं, भारत की पहली हिंदी और हिंग्लिश टीटीएस मॉडल।")
```

## Output
Audio is rendered directly inside the notebook using IPython.display.Audio.

## Model Details
	•	🧠 3B parameter autoregressive model
	•	🗣️ 4 expressive Indian voices
	•	⚡ Low-latency, streaming-capable
	•	📂 Open-source: Hugging Face model card

## Try It Yourself

Clone the repo and run the notebook on Google Colab or Jupyter with a GPU runtime:

Colab: https://colab.research.google.com/drive/1LcrZSE-muJNXROc5A18aQZSIJJoxGei5?usp=sharing

```
git clone https://github.com/arpitpatelsitapur/Testing-Veena.git
cd Testing-Veena
```



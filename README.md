# ✨ AI Magic — Live Interactive Demos

> Real artificial intelligence running in your browser. No tricks, no illusions.

🔗 **Live Demo:** https://htekdev.github.io/ai-demo/

## What's Inside

Three live AI demos powered by real machine learning models:

### 🎭 Emotion Detector
Type any text and the AI breaks down the emotional content — detecting joy, love, surprise, fear, anger, sadness, and more. Powered by `j-hartmann/emotion-english-distilroberta-base`.

### 🌎 AI Translator
Real-time Spanish ↔ English translation using neural machine translation. Powered by `Helsinki-NLP/opus-mt` models.

### 👁️ Image Recognition
Upload any photo and the AI identifies what's in it — trained on 14 million images across 1,000 categories. Powered by `google/vit-base-patch16-224`.

## Tech Stack

- Pure HTML/CSS/JavaScript (no build tools)
- [HuggingFace Inference API](https://huggingface.co/inference-api) — free, real AI models
- Deployed on GitHub Pages

## Notes

- First request to each model may take ~15-20 seconds (model warm-up)
- Works great on mobile — image recognizer can use your camera!
- No data is stored — everything is processed in real-time

---
Built with ❤️ to showcase the power of modern AI.

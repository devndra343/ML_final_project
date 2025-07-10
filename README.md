# ML_final_project
Transformer-based NLP model for next-word prediction using GPT-2 and Hugging Face
# Next Word Predictor using Transformers

This project implements a next-word prediction model using a pre-trained GPT-2 transformer from Hugging Face. It includes fine-tuning on the WikiText-2 dataset and evaluation with accuracy and perplexity metrics.

## 📚 Dataset
- WikiText-2 (via Hugging Face `datasets` library)

## 🛠️ Tech Stack
- Transformers (Hugging Face)
- PyTorch
- Evaluate (for metrics)
- Gradio (optional for demo)

## 🚀 Features
- Fine-tunes GPT-2 for next word prediction
- Evaluates with top-1 accuracy
- Optional web interface with Gradio

## 📦 Setup
```bash
pip install -r requirements.txt

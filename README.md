# Multi-Model Medical Chatbot

## Overview

This project is a multimodal AI-based Health & Wellness Assistant built using Python and Gradio.

It accepts text, images, and audio as input and generates text and voice responses. The chatbot is designed to provide general health and wellness information and includes a safety notice to avoid providing medical diagnoses or treatment advice.

## Features

- Text-based health queries
- Image understanding using LLaVA
- Speech-to-text using Whisper
- Text-to-speech using gTTS
- Voice response generation
- Simple Gradio interface

## Technologies Used

- Python
- Gradio
- PyTorch
- Transformers
- LLaVA
- Whisper
- gTTS
- Librosa
- Pillow

## Project Structure

```
MULTI_MODEL_MEDICAL_CHATBOT/
│
├── MULTI_MODEL_MEDICAL_CHATBOT.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

## Installation

Install the required packages:

```bash
pip install -r requirements.txt
```

## Run

Open the notebook in Google Colab and run all cells.

## Inputs

- Text
- Image (Optional)
- Audio (Optional)

## Outputs

- AI-generated health information
- Voice response

## Note

This project provides general wellness information only and should not be used as a substitute for professional medical advice.

## Author

Sathwika M

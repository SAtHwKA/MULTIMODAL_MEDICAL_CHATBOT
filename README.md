# 🩺 Multi-Modal Medical Chatbot

The Multi-Modal Medical Chatbot is a multimodal AI application developed using Python and Gradio. It accepts text, image, and audio inputs to generate informative health and wellness responses. The system integrates vision-language and speech recognition models to provide a simple interactive experience.

---

## Overview

The Multi-Model Medical Chatbot integrates multiple AI models to support different input modalities. Users can ask health-related questions by entering text, uploading an image, or providing an audio recording. The chatbot processes the input and generates both text and voice responses.

---

## Features

- Text-based health queries
- Image understanding using LLaVA
- Audio input support
- Speech-to-text conversion using Whisper
- Voice response generation using gTTS
- Interactive Gradio interface

---

## Technologies Used

- Python
- Gradio
- PyTorch
- Transformers
- LLaVA
- Whisper
- gTTS

---

## Notebook Workflow

### 1. Environment Setup
Install the required libraries and dependencies.

### 2. Model Initialization
Load the LLaVA vision-language model, Whisper speech recognition model, and gTTS for voice generation.

### 3. Input Processing
Accept user input in the form of:
- Text
- Image *(Optional)*
- Audio *(Optional)*

### 4. Integrated LLaVA Interface
Launch the live Gradio chatbot interface where users can interact with the chatbot by submitting text, images, or audio queries. The chatbot processes the inputs and generates AI-powered text and voice responses in real time.

---

## Installation

Install the required packages using:

```bash
pip install -r requirements.txt
```

---

## Running the Project

1. Open the notebook in Google Colab.
2. Install the required dependencies.
3. Run the notebook cells sequentially.
4. Launch the Gradio interface.
5. Interact with the chatbot using text, image, or audio input.

---

## Input

- Text
- Image 
- Audio 

---

## Output

- AI-generated text response
- AI-generated voice response
- Live interactive chatbot interface

---

## Disclaimer

This project is intended for educational and informational purposes only. It provides general health and wellness information and should not be considered a substitute for professional medical advice, diagnosis, or treatment. Users should consult qualified healthcare professionals for medical concerns.

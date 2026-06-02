# Story-to-visual
Multimodal AI project combining text-to-image generation and neural text-to-speech for automated story visualization and narration.
# Story-to-Audio & Visual Generator

An AI-powered multimodal application that converts written stories into narrated audio and AI-generated visual scenes.

## Overview

This project allows users to enter a story and automatically generates:

* 🎧 Audio narration using a Neural Text-to-Speech (TTS) model
* 🖼️ Three AI-generated scene illustrations using Stable Diffusion
* 🌐 Interactive web interface built with Gradio

The application demonstrates how multiple AI models can work together to transform text into different media formats.

## Features

* Story narration with natural-sounding AI voice
* Automatic story-to-scene conversion
* AI image generation using Stable Diffusion
* Interactive Gradio user interface
* GPU and CPU support
* Hugging Face Spaces deployment ready

## AI Models Used

### 1. Text-to-Image Model

**Stable Diffusion v1.5**

Used to generate visual scenes from story paragraphs.

Pipeline Components:

* CLIP Text Encoder
* UNet Diffusion Network
* Variational Autoencoder (VAE)

### 2. Text-to-Speech (TTS) Model

**Microsoft Edge Neural TTS**

Used to convert story text into natural-sounding speech narration.

## Tech Stack

* Python
* Gradio
* PyTorch
* Diffusers
* Transformers
* Edge-TTS
* Hugging Face Spaces

## Workflow

User Story
↓
Story Segmentation
↓
Text-to-Speech Generation
↓
Stable Diffusion Image Generation
↓
Audio + Scene Images Displayed

## Example Output

### Input Story

A short three-paragraph adventure story.

### Generated Results

* Narrated audio file
* Scene 1 illustration
* Scene 2 illustration
* Scene 3 illustration

## Screenshots

### Generated Scene 1

(Add image here)

### Generated Scene 2

(Add image here)

### Generated Scene 3

(Add image here)

## Installation

```bash
pip install -r requirements.txt
```

## Run Locally

```bash
python app.py
```

## Deployment

The project is deployed on Hugging Face Spaces.

Live Demo: [(https://huggingface.co/spaces/Anublossom/story-visualizer)]

## Learning Outcomes

This project helped me understand:

* Diffusion Models
* Text Embeddings
* Stable Diffusion Architecture
* Neural Text-to-Speech Systems
* Gradio Application Development
* Hugging Face Deployment
* Multimodal AI Applications

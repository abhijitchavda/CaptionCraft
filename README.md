# CaptionCraft

Transform your photos into shareable moments with AI-generated, attention-grabbing captions. CaptionCraft uses state-of-the-art AI models to analyze images and generate catchy captions for your social media posts.

## Features

- **Image Upload**: Upload an image directly from your device to generate a caption.
- **Image URL**: Provide an image URL to generate a caption for the image hosted online.
- **AI-Powered**: Utilizes advanced AI models for accurate image description and creative caption generation.

## Installation

To run CaptionCraft locally, you need to install the following dependencies:

```bash
pip install transformers torch pillow requests gradio langchain-experimental
```

Make sure you also have Ollama running on localhost at port 11434 with the “mistral:instruct” model downloaded.

## Overview

Here’s a brief overview of the main components:

- **BLIP Model**: Used to generate descriptions of the images using HuggingFace provided library.
- **Ollama**: Utilized for creating catchy captions based on the image descriptions.
- **Gradio**: Provides a user-friendly interface for interacting with the application.

## Usage

- **Upload an Image**: Click on “Upload an image” to upload an image file from your device. The app will generate a catchy caption for the image.
- **Provide Image URL**: Click on “Provide image URL” to paste an image URL. The app will fetch the image and generate a caption.

## UI
![Upload Image](https://github.com/abhijitchavda/CaptionCraft/blob/main/UIUploadImage.jpg?raw=true)
![Upload Image URL](https://github.com/abhijitchavda/CaptionCraft/blob/main/UIUploadImageURL.jpg?raw=true)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any improvements or suggestions.

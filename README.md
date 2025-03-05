# StableDiffusion_from_Scratch
Stable Diffusion Model from Scratch (PyTorch Implementation)

## Overview

This repository contains a complete, end-to-end implementation of Stable Diffusion in PyTorch, built from the ground up.  It's designed as a learning resource, providing a clear and detailed walkthrough of the entire text-to-image and image-to-image pipeline.  Following the excellent tutorial by [Umar Jamil](https://www.youtube.com/watch?v=ZBKpAp_6TGI&ab_channel=UmarJamil), this project offers a practical understanding of the core components of Stable Diffusion.

## Key Features

*   **Complete Pipeline:** Implements the full Stable Diffusion pipeline, including:
    *   **Variational Autoencoder (VAE):**  For encoding images into a latent space and decoding them back.
    *   **U-Net:** The core denoising network responsible for iteratively removing noise from latent representations.
    *   **CLIP Text Encoder:**  Encodes text prompts into a format that the U-Net can understand.
    *   **DDPM Scheduler:**  Manages the noise addition and removal process.
*   **Text-to-Image Generation:** Generate images from textual descriptions.
*   **Image-to-Image Transformation:**  Modify existing images based on text prompts.
*   **From-Scratch Implementation:**  No reliance on high-level Stable Diffusion libraries, promoting deep understanding.
*   **Detailed Code Comments:**  Extensive comments throughout the code explain the purpose and functionality of each section.

## Overview

This project is a complete PyTorch implementation of a Stable Diffusion model, built entirely from scratch by following an excellent educational resource. The project captures the full text-to-image and image-to-image generation pipeline, providing a deep dive into the core concepts and architectures that power modern generative models.

## Key Components

Variational Autoencoder (VAE): Encodes and decodes image data into a latent space, enabling efficient and meaningful representations of visual data.

U-Net Architecture: A powerful denoising model that learns to gradually transform noisy latent representations into coherent and high-quality images.

Text Encoder: Conditions the image generation on text prompts, allowing the model to align visual outputs with descriptive language inputs.

Diffusion Process: Implements the forward and reverse diffusion steps, systematically adding and removing noise to train the model for generating realistic and diverse outputs.

## Features

Text-to-Image Generation: Generate detailed and high-quality images from natural language prompts.

Image-to-Image Translation: Transform existing images by conditioning on textual descriptions for style transfer and content generation.

Modular PyTorch Code: Easy-to-read and well-structured codebase, ensuring clarity and extensibility.

Complete Training Pipeline: End-to-end training process, including data preprocessing, model training, and evaluation.


## Result:
prompt: "A dog with sunglasses, looking at camera, highly detailed, ultra sharp, cinematic, 100mm lens, 8k resolution."
![output](https://github.com/user-attachments/assets/02eaf068-b963-4998-b0ce-aaea9e4332ec)


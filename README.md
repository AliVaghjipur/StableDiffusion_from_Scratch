# StableDiffusion_from_Scratch
Stable Diffusion Model from Scratch (PyTorch Implementation)

## Overview

This repository contains a complete, end-to-end implementation of Stable Diffusion in PyTorch, built from the ground up.  It's designed as a learning resource, providing a clear and detailed walkthrough of the entire text-to-image and image-to-image pipeline.  This project is built to gain practical understanding of the core components of Stable Diffusion. The formulas are used from the DDPM papers (also mentioned in the comments with the equation number)

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

## Result:
prompt: "A dog with sunglasses, looking at camera, highly detailed, ultra sharp, cinematic, 100mm lens, 8k resolution."
![output](https://github.com/user-attachments/assets/02eaf068-b963-4998-b0ce-aaea9e4332ec)


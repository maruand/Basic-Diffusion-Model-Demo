# Project title: Basic Diffusion Model for Simple Geometric Shape Generation

## Overview
This repository contains a basic conceptual demonstration of a Denoising Diffusion Probabilistc Model (DDPM) implemented using PyTorch. The proroject focuses on generating two simple 2D geometric shapes (rectangles, circles)  from random noise, showcasing a foundational understanding of diffusion-based generative models. This work serves as a practical exploration of AI methods relevant to many mainstream generative models such as Stable diffusion and DALL-E

## Project Goals
The primary objectives of this project were to:

* Generate a synthetic dataset of simple geometric shapes using Python's `OpenCV` and `NumPy`.
* Implement a simplified DDPM from scratch in PyTorch, covering the forward (noising) and reverse (denoising) processes.
* Develop a U-Net architecture as the noise prediction network, incorporating timestep conditioning.
* Train the diffusion model on the generated dataset.
* Demonstrate image generation by sampling from pure noise and iteratively denoising.
* Document the process and findings in a clear, concise Jupyter Notebook.
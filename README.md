# Predictive-GAN-Video-Frames
Predictive Generative Adversarial Networks (GANs) for Video Frame Prediction 🎥
This repository contains the implementation of a Predictive GAN designed for video frame prediction using the UCF101 dataset. The model employs a GAN-based architecture with a residual-based generator and a sequence discriminator to improve temporal consistency in generated video frames. The project includes dataset preprocessing, model architecture details, training strategy, and evaluation metrics.

⚡ Key Features:

Uses Conv2D & ConvTranspose2D layers for feature extraction and upsampling

Implements residual blocks for improved gradient flow

Employs both frame and sequence discriminators for better realism and temporal coherence

Tracks training progress with L1 loss, Log Similarity Loss, and Discriminator Losses

🔧 Limitations & Future Work:

Results are affected by limited computational power and training time

Additional GAN-specific optimizations could enhance perceptual quality

Future improvements include better architectures and GPU-based training

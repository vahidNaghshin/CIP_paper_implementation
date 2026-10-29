# Educational CLIP from Scratch 🚀
A clean, lightweight, and educational implementation of OpenAI's CLIP (Contrastive Language-Image Pretraining) model built entirely from scratch in PyTorch.

This repository is designed to demonstrate the core mathematical and structural concepts of contrastive representation learning without the overhead of massive production models.

✨ # Key Features & Concepts Covered
Dual Encoder Architecture: Features a modular Image Encoder (CNN-based backbone) and a Text Encoder (Embedding + Recurrent unit) projected into a shared latent space.
Symmetric Contrastive Loss: A native PyTorch implementation of the symmetric cross-entropy loss over joint-space similarity matrices using a learnable temperature scale parameter ($\tau$$\tau$).
Custom Data Pipeline: Includes a simplified text tokenizer, vocabulary constructor, and custom PyTorch Dataset/DataLoader pipeline built without third-party dependencies.
Zero-Shot Inference: Demonstrates out-of-the-box cross-modal classification matching unlabeled images to textual prompts with high statistical confidence.
Colab Ready: Designed to compile, run, and converge in minutes on consumer-grade CPUs or single GPUs.

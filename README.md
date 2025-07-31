# Underwater-Image-Enhancement-with-Multi-Scale-Residual-Attention-Network-MSRAN

This repository implements a deep learning-based approach for enhancing underwater images using a **Multi-Scale Residual Attention Network (MSRAN)**. The model is designed to address common underwater image issues such as low contrast, color distortion, and blurriness by integrating multi-scale feature extraction and spatial attention mechanisms.

# Key Features:
Multi-Scale Residual Learning: Extracts features at multiple scales to capture both global structures and fine details.

Attention Mechanism: Enhances important regions in the image using spatial attention to focus on degraded areas.

End-to-End Learning: Fully convolutional network trained to directly restore degraded underwater images to high-quality outputs.

Real-Time Inference: Efficient architecture for fast processing suitable for real-time applications such as underwater robotics or marine biology.

# Applications:
Marine exploration and research

Underwater photography and videography

Autonomous underwater vehicles (AUVs) vision systems

Preprocessing for object detection and tracking in underwater scenes

# Repository Contents:
model/: PyTorch implementation of MSRAN

dataset/: Sample underwater image dataset and data loader scripts

train.py: Script to train the model

evaluate.py: Script to test and evaluate model performance

results/: Enhanced output images for visual comparison

requirements.txt: List of required packages

README.md: Documentation for setup, usage, and model details

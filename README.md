# CLIP-Handwritten-Recognition

This project implements a CLIP-style model for learning joint image-text embeddings on the MNIST dataset.

## Features

• Developed a CLIP-style model for handwritten digit recognition and representation learning.  

• Encodes images with a residual CNN and labels with a lightweight text encoder.  

• Supports both classification and image similarity tasks.

## Usage

1. Install dependencies: `pip install -r requirements.txt`  

2. Train the model: `python train.py`  

3. Run inference: `python inference.py`  

## Future Improvements

• Explore larger text embeddings for richer semantic representations.  

• Incorporate data augmentation to improve generalization.  

• Evaluate on more complex datasets beyond MNIST.

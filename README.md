# Experiment 8: Generation of Synthetic Images Using a Generative Adversarial Network (GAN)

## Aim
To implement and train a Generative Adversarial Network (GAN) to generate synthetic images by training a Generator and a Discriminator in an adversarial learning framework.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab
- GitHub

## Dataset
The MNIST dataset is used for training the GAN.

- Contains 70,000 handwritten digit images.
- Image dimensions: 28 × 28 pixels.
- Pixel values are normalized between -1 and 1.
- Contains digits from 0 to 9.

## Objectives
- Understand the architecture and working of GANs.
- Implement Generator and Discriminator models.
- Prepare and normalize image datasets.
- Train GAN using adversarial learning.
- Generate synthetic handwritten digit images.
- Visualize and compare original and generated images.
- Monitor Generator and Discriminator losses.

## GAN Architecture

A GAN consists of two neural networks:

### 1. Generator
- Takes random noise vectors as input.
- Uses neural network layers to generate synthetic images.
- Tries to produce realistic images that can fool the Discriminator.

### 2. Discriminator
- Takes real and generated images as input.
- Classifies images as real or fake.
- Helps the Generator improve image quality.

Both networks compete with each other during training to generate realistic images.

## Implementation

The experiment is divided into four tasks:

### Task A: Dataset Preparation
- Import required Python libraries.
- Load the MNIST dataset.
- Display sample handwritten digit images.
- Explore image dimensions and pixel values.
- Normalize and reshape images.
- Prepare batches for training.

### Task B: Generator and Discriminator Implementation
- Build the Generator model using Dense and Conv2DTranspose layers.
- Build the Discriminator using Conv2D and Dense layers.
- Define loss functions and optimizers.
- Display model summaries.

### Task C: GAN Training and Performance Monitoring
- Train the Discriminator using real and generated images.
- Train the Generator to produce realistic images.
- Perform adversarial training for multiple epochs.
- Record Generator and Discriminator losses.
- Plot training loss graphs.
- Display generated synthetic images.

### Task D: Feature Visualization and Experiment Management
- Generate new synthetic images using random noise.
- Display generated images.
- Compare original and synthetic images.
- Observe image quality and diversity.
- Save the trained Generator model.
- Save generated images.


## Applications of GANs
- Medical image generation.
- Image enhancement and restoration.
- Face generation and editing.
- Image-to-image translation.
- Data augmentation.

## Result
A Generative Adversarial Network was successfully implemented and trained using the MNIST dataset. The Generator produced synthetic handwritten digit images from random noise, and the generated images were visualized and compared with original dataset samples.

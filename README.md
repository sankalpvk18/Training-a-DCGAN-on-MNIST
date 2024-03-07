# DCGAN for MNIST Digit Generation

This repository contains code for training a Deep Convolutional Generative Adversarial Network (DCGAN) on the MNIST dataset to generate realistic digit images.

## Overview

DCGAN is a type of generative model that uses convolutional neural networks (CNNs) to generate realistic images. In this implementation, we use TensorFlow and Keras to build and train the DCGAN model.

## Code Structure

The code consists of the following components:

1. **Plot Images Function**: A function to plot a grid of generated images.
2. **Generate Samples Callback**: A callback class to generate images from the generator model at the end of each epoch.
3. **Discriminator Model**: Defines the architecture of the discriminator network.
4. **Generator Model**: Defines the architecture of the generator network.
5. **DCGAN Class**: Combines the discriminator and generator models and defines the training step.
6. **Training Function**: Loads the MNIST dataset, builds the discriminator and generator, compiles the DCGAN, and trains the model.

## How to Use

1. Clone this repository to your local machine.
2. Install the required dependencies (`TensorFlow`, `NumPy`, `Matplotlib`).
3. Run the `train_dcgan_mnist()` function to train the DCGAN on the MNIST dataset.

## Generated Images

After training, the DCGAN will generate images resembling handwritten digits. These images will be saved in the `generated_images` directory.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## References

- TensorFlow Documentation: [https://www.tensorflow.org/](https://www.tensorflow.org/)
- DCGAN Paper: [https://arxiv.org/abs/1511.06434](https://arxiv.org/abs/1511.06434)

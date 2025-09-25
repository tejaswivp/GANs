# GANs
Generative Adversarial Network (GAN) for 2D Data Generation

This project implements a simple GAN in PyTorch to generate synthetic 2D data resembling a noisy sinusoidal distribution. Key features include:

Discriminator: Multi-layer fully connected network with ReLU activations and dropout, trained to distinguish real from generated samples.

Generator: Multi-layer fully connected network mapping 2D latent vectors to 2D output points.

Training: Uses Binary Cross-Entropy loss for adversarial training, with alternating optimization for discriminator and generator.

Visualization: Plots training data, discriminator/generator losses, and generated samples to evaluate GAN performance.

The project demonstrates fundamental GAN concepts, including latent space sampling, adversarial loss, and training stability.

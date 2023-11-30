# Denoising Diffusion Probabilistic Model

Implementation of model training, inference of a basic diffusion model - both forward and reverse diffusion processes.
Mathematical paper at https://arxiv.org/pdf/2006.11239.pdf by Jon Ho.
Uses Pytorch, Lightning

Uses CIFAR-10 dataset (https://www.cs.toronto.edu/~kriz/cifar.html) to train the Unet and infers a GIF from the latent space, showing progressive denoising.
Also includes a notebook to generate noise to any image (hardcoded jpg)

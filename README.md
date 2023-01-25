# Generating ~~bums~~ people with a deep convolutional GAN

Dataset: https://www.kaggle.com/datasets/greatgamedota/ffhq-face-data-set

Trying to squeeze every last drop of quality from DCGAN architecture with mininmal effort.

Contains:
- standard tricks (reflect padding, betas);
- normalization and `Tanh()` output;
- some augmentations;
- weight initialization according to DCGAN paper;
- SiLU;
- PixelNorm (akin to ProGAN/StyleGAN)



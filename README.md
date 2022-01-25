# Generative Adversarial Networks (GANs) - A Gentle Introduction

Author: Umberto Michelucci [umberto.michelucci@toelt.ai](mailto:umberto.michelucci@toelt.ai).

This repository contains the material for a Gentle Introduction to GANs. Here you can find

## Main Content

- [A Gentle Introduction to GANs (PDF)](https://github.com/toelt-llc/GANs-TensorFlow/blob/main/docs/michelucci_GANs.pdf) - A paper with a short introduction on the main idea about GANs
- Under [code](https://github.com/toelt-llc/GANs-TensorFlow/tree/main/code) you can find some examples.

## Complete Examples

In case you are interested, you can find compelte examples at [httsp://adl.toelt.ai](https://adl.toelt.ai). In particular you can
find the complete code for a generic GAN applied to MNIST [HERE](http://adl.toelt.ai/GAN/GAN_with_MNIST.html).

# Code Folder

In the code folder the following files are relevant:

- [Example of a GAN with MNIST](https://github.com/toelt-llc/GANs-TensorFlow/blob/main/code/GAN_with_MNIST.ipynb) 
- There are several h5 files that are used by the notebook. Those are the trained generator and discriminator. You should not need to use them directly.
- [GAN_Fashion_MNIST.py](https://github.com/toelt-llc/GANs-TensorFlow/blob/main/code/GAN_Fashion_MNIST.py) this file is a script that will train a GAN on MNIST and save the generator model as ```generator.h5``` (already avaialble in the folder). This script can be used when letting the training run for a few hours on a server.
- [Example of a conditional GAN with MNIST](https://github.com/toelt-llc/GANs-TensorFlow/blob/main/code/Conditional_GAN_With_MNIST.ipynb)

The other folders contain output images and are not directly relevant.
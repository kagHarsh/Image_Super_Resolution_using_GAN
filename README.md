# Image_Super_Resolution_using_GAN
This repository contains the code for implementing image super-resolution using a Generative Adversarial Network (GAN). The GAN architecture used is based on the SRGAN (Super-Resolution GAN) model.

# Introduction
Image super-resolution refers to the task of generating high-resolution images from low-resolution inputs. The goal is to enhance the visual quality and details of an image, making it appear sharper and more detailed. GANs have shown promising results in the field of image super-resolution by learning the mapping between low-resolution and high-resolution images.

# Prerequisites
To run the code in this repository, you need the following dependencies:
- Python 3.10.11
- TensorFlow (version: 2.12.0)
- Keras (version: 2.12.0)
- NumPy
- Matplotlib

# Model Architecture
The GAN model used in this repository follows the SRGAN architecture. It consists of a generator network and a discriminator network. The generator network takes a low-resolution image as input and generates a high-resolution image. The discriminator network distinguishes between the generated high-resolution images and real high-resolution images. The two networks are trained simultaneously, with the generator aiming to generate realistic high-resolution images that can fool the discriminator.

![Model Architecture](https://drive.google.com/file/d/1XWxR6w7yMYuOeVx-Fg0YWsyXrG7mofeW/view?usp=share_link)

# Results
Sample results obtained from the trained model can be found in the 'results' directory.

# Acknowledgements
- This project is inspired by the SRGAN paper by Ledig et al. (2017).
- The initial code structure and architecture are based on the work of Ledig et al.

# References
Ledig, C., Theis, L., Huszár, F., Caballero, J., Cunningham, A., Acosta, A., ... & Shi, W. (2017). Photo-realistic single image super-resolution using a generative adversarial network. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 4681-4690).

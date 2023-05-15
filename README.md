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

<img width="550" alt="image" src="https://github.com/kagHarsh/Image_Super_Resolution_using_GAN/assets/124779369/802c8d39-e488-4994-8567-0335af3af4a7">

# Datset
You can download the dataset from the [dataset](https://www.kaggle.com/datasets/paulrohan2020/mirflickr25k)


# Results
Sample results obtained from the trained model can be found in the 'results' directory.

# Acknowledgements
- This project is inspired by the SRGAN paper by Ledig et al. (2017).
- The initial code structure and architecture are based on the work of Ledig et al.

# References
Ledig, C., Theis, L., Huszár, F., Caballero, J., Cunningham, A., Acosta, A., ... & Shi, W. (2017). Photo-realistic single image super-resolution using a generative adversarial network. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 4681-4690).

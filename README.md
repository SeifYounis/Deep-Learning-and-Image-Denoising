# The Importance of Objective Methods for the Evaluation of Deep Learning Image Processing Devices

## Intro
This is an ongoing project investigating the efficacy of generative adversarial networks in removing noise from medical scans, and the degree to which these networks' methods of constructing realistic high-quality xrays from noisy input undermines necessary objectivity in processing raw medical image data.

## Overview

## References
1. [Denoising Autoencoders](#denoising-autoencoders)
2. [Generative Adversarial Networks](#generative-adversarial-networks-gan)
3. [Network Optimization]()
3. [Simulating Image Noise](#simulating-x-ray-image-noise)
---
### Denoising Autoencoders

#### Tutorials
- [Tensorflow Intro to Autoencoders](https://www.tensorflow.org/tutorials/generative/autoencoder?hl=en)
- [Keras Denoising Autoencoder](https://keras.io/examples/vision/autoencoder)

#### Research
- Medical Image Denoising Using Convolutional Denoising Autoencoders [[paper]](https://arxiv.org/pdf/1608.04667.pdf) [[code]](https://github.com/adam-mah/Medical-Image-Denoising/tree/53101562b75b44ec8722486a54d17cc961b4bbea)
- Learning Deep Representations Using Convolutional Auto-Encoders with Symmetric Skip Connections [[paper]](https://arxiv.org/pdf/1611.09119.pdf) [[code]](https://github.com/MS1997/Autoencoders-with-skip-connections)
- Hyperspectral X-Ray Denoising: Model-Based and Data-Driven Solutions [[paper]](https://nicobonne.github.io/assets/papers/eusipco_2019.pdf)

---

### Generative Adversarial Networks (GAN)

#### Tutorials
- [Tensorflow DCGAN](https://www.tensorflow.org/tutorials/generative/dcgan?hl=en)
- [Tensorflow ESRGAN](https://www.tensorflow.org/hub/tutorials/image_enhancing)

#### Research
- Low Dose CT Image Denoising Using a Generative Adversarial Network with Wasserstein Distance and Perceptual Loss [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6021013/pdf/nihms973044.pdf) [[code]](https://github.com/yyqqss09/ldct_denoising)
- Digital Radiography Image Denoising Using a Generative Adversarial Network [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6130336/pdf/xst-26-xst17356.pdf)
---

### Network Optimization
1. VGG Loss [[paper]](https://paperswithcode.com/method/vgg-loss) [[code]](https://colab.research.google.com/gist/jvishnuvardhan/dfd2cf563b1a3e255455b3c54e64d3b8/tf_30534_customloss.ipynb#scrollTo=e3TFz1m2n1sj) [[docs]](https://keras.io/api/applications/vgg/)

---
### Simulating X-ray Image Noise

#### Research
- A Technique for Simulating the Effect of Dose Reduction on Image Quality in Digital Chest Radiography [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3043684/#CR4)
- 
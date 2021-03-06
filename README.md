# Implementation of various GANs with TensorFlow slim

This repository is a collection of various GAN models.


## Getting Started

### Prerequisites
* `TensorFlow` 1.10.0
* Python 3.6
* Python libraries:
  * `numpy`, `matplotlib`, `PIL`
* Jupyter notebook
* OS X and Linux (Not validated on Windows but probably it would work)


## Generative Adversarial Networks
* Original GAN paper [arXiv:1406.2661](https://arxiv.org/abs/1406.2661)
* [gan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.slim/blob/master/gan.ipynb)
<div align="center">
<img src='./results/gan.result.ckpt.149969.jpg'>
</div>



## Deep Convoluational GAN
* Unsupervised Representation Learning with Deep Convolutional
Generative Adversarial Networks paper [arXiv:1511.06434](https://arxiv.org/abs/1511.06434)
* [dcgan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.slim/blob/master/dcgan.ipynb)
<div align="center">
<img src='./results/dcgan.result.ckpt.28112.jpg'>
</div>


## Conditional GAN
* Conditional Generative Adversarial Nets [arXiv:1411.1784](https://arxiv.org/abs/1411.1784)
* [cgan_based_on_dcgan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.slim/blob/master/cgan_based_on_dcgan.ipynb)
<div align="center">
<img src='./results/cgan.result.ckpt.18745.jpg'>
</div>


## InfoGAN

* `infogan.ipynb`
* InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets [arXiv:1606.03657](https://arxiv.org/abs/1606.03657)


## Bidirectional GAN

* `bigan.ipynb`
* Adversarial Feature Learning [arXiv:1605.09782](https://arxiv.org/abs/1605.09782)


## Least Squares GAN

* `lsgan.ipynb`
* Least Squares Generative Adversarial Networks [arXiv:1611.04076](https://arxiv.org/abs/1611.04076)


## Wasserstein GAN

* `wgan.ipynb`
* Wasserstein GAN [arXiv:1701.07875](https://arxiv.org/abs/1701.07875)


## Boundary Equilibrium GAN

* `began.ipynb`
* BEGAN: Boundary Equilibrium Generative Adversarial Networks [arXiv:1703.10717](https://arxiv.org/abs/1703.10717)


### Author
Il Gu Yi

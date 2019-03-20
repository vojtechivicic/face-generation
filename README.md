# Face Generation
Pytorch implementation of **generative adversarial network (GAN)** for generating new images of faces. 

The model uses **DCGAN architecture** proposed in [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434), it is trained on [CelebFaces Attributes (CelebA) Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). 

To stabilize training, labels of real images are **smoothed** ([Improved Techniques for Training GANs](https://arxiv.org/abs/1606.03498)) and random **Gaussian noise** is added to all images ([Amortised MAP Inference for Image Super-resolution](https://arxiv.org/abs/1610.04490))

This is the fifth assigment for [Udacity Deep Learning Nanodegree](https://eu.udacity.com/course/deep-learning-nanodegree--nd101).

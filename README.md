# Image-to-Image-using-GANs.
We investigate conditional adversarial networks as a general-purpose solution to image-to-image translation problems. These networks not only learn the mapping from input image to output image, but also learn a loss function to train this mapping with tensorflow implementation.

The original code can be found [here](https://www.tensorflow.org/tutorials/generative/pix2pix) on the Google co-lab, but here, I tried to do some changes in the model and presentation of the code's ouput to gain more accessibility of the code in practical application.

Tensorflow implementation of pix2pix. Learns a mapping from input images to output images, like these examples from the original paper:
<img src="https://phillipi.github.io/pix2pix/images/teaser_v3.png" width="900px"/>



## Setup
 ### Prerequisites
 --> Tensorflow 2.0.0
#### Recommended
*Linux with Tensorflow GPU edition + cuDNN

# Abstract
We investigate conditional adversarial networks as a general-purpose solution to image-to-image translation problems. These networks not only learn the mapping from input image to output image, but also learn a loss function to train this mapping. This makes it possible to apply the same generic approach to problems that traditionally would require very different loss formulations. We demonstrate that this approach is effective at synthesizing photos from label maps, reconstructing objects from edge maps, and colorizing images, among other tasks. As a community, we no longer hand-engineer our mapping functions, and this work suggests we can achieve reasonable results without hand-engineering our loss functions either.


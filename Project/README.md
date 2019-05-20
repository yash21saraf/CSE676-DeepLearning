### Image colorization 

The topic of image colorization has been explored in a variety of ways, some involving deep learning, others using traditional image processing. One of the interesting approaches has been using the Generative Adverserial Networks. 

The GANs are networks which contain two halves i.e. Generator an Discriminator which is trained using the Min max loss function. A lot of variations of GANs have been produced since then. One such approach is pix2pix or conditional GAN where the loss function is dependent on paired images as well as GAN loss. 

Here we have used three such architectures in our study to understand the use of GAN well-
- One such approach is using traditional cycle GAN, where we don't use pair of images but train the network using the cycle consistency loss, identity loss, along with GAN loss. 
- One modification made to the cycleGAN archtecture is by modifying the Discriminator architecture by using a Capsule Network instead of Patch GAN. 
- Another approach used is traditional pix2pix architecture. 

In all three approaches the Generator architecture is a U-net architecture. 

The dataset was downloaded from the following-
- [Visual Geometry Group Home Page](http://www.robots.ox.ac.uk/~vgg/data/flowers/)

For references the following were used-
- [GitHub - eriklindernoren/Keras-GAN: Keras implementations of Generative Adversarial Networks.](https://github.com/eriklindernoren/Keras-GAN)
- [GitHub - gusgad/capsule-GAN: Code for my Master thesis on "Capsule Architecture as a Discriminator in Generative Adversarial Networks".](https://github.com/gusgad/capsule-GAN)
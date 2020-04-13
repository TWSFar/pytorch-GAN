## GANs for MNIST / CIFAR10

* includes model class definitions + training scripts
* tested with pytorch 1.0+, python >3.7
* generates images the same size as the dataset images


## mnist
Generates images the size of the MNIST dataset (28x28), using an architecture based on the [DCGAN](http://arxiv.org/abs/1511.06434) paper. Trained for 100 epochs. Weights [here](https://github.com/csinva/pytorch_gan_pretrained/tree/master/mnist_dcgan/weights).


## cifar10
The cifar10 gan is from the pytorch examples repo and implements the DCGAN paper. It required only minor alterations to generate images the size of the cifar10 dataset (32x32x3). Trained for 200 epochs. Weights here.

## cifar100
Similiar to the above gans, the cifar100 gan here generates 32x32x1 images for generating grayscale images. Trained for 200 epochs. Weights here. There are also weights/code for generating images which are 34x45x1.


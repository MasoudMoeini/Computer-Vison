# Resolution Refinement for Enlarged Scale Images Using GANs

Recent innovations in Deep Learning (DL) and Convolutional Neural Networks (CNN) in computer vision have enabled us to develop sophisticated methods to improve traditional approaches. This work represents a novel method to get a super-resolution version of images from low scale images by applying a Genera- tive Adversarial Networks (GANs). The idea is that based on GANs we assume the input for the Generator network is sequences of low scale images (8 × 8) and the Generator part generates higher scale images ( 32 × 32) with four times up- scaling. For this purpose, the Generator network is trained with a synthetic loss function which consists of an adversarial loss and pixel-wise Mean Square Error (MSE) Loss. The adversarial loss leads the Generator network toward creating of the super-resolution images based on the Discriminator network learning ar- gument, that is trained to differentiate between real and fake images. The MSE loss function conceptually improves the performance of the Generator network and in supervised approach, computes the error between the generated super-resolved images and the original images as a ground truth. 

After cloning code please download CIFAR-10 dataset from: https://www.cs.toronto.edu/~kriz/cifar.html
(CIFAR-100 python version), and extract dataset in code folder.
Run file: IRgan.ipynb  to prepare input data for purpose network
Main file: FinalEvaluation_Main.ipynb 

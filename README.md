# Resolution Refinement for Enlarged Scale Images Using GANs
 
Recent innovations in Deep Learning (DL) and Convolutional Neural Network (CNN) in computer vision 
has enabled us to develop sophisticated methods to improve traditional approaches.
Based on CIFAR10 dataset,I developed a novel method in order to get high resolution version of enlarged 
scale images from low scale images by applying unsupervised deep learning approach. 
The idea is that based on Generative Adversarial Networks (GANs) we assume the input for
Generator network is sequences of low scale (e.g 8 x 8) images and in GANs the Generator part generates some random
noisy higher scale images (e.g 32 x 32) for each input image and the Discriminator based on the original
images detects the desired image among the generated random noisy images. 

After cloning code please download CIFAR-10 dataset from: https://www.cs.toronto.edu/~kriz/cifar.html
(CIFAR-100 python version), and extract dataset in code folder.

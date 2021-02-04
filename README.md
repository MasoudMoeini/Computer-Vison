# Resolution Refinement for Enlarged Scale Images Using GANs
Click on:<br/>
- FinalEvaluation_Main.ipynb file to see prediction model with GANs(two stream of CNN using tensorflow) and visulization.
<br/>
<br/>
If you are Intereseted to run the repository make sure that you have already jupyter nootbook and necessary python libraries installed at your pc.<br/>
1)Clone repository (Reference dataset CIFAR-10 https://www.cs.toronto.edu/~kriz/cifar.html ) already was downloaded and included in repository <br/>
2)Run file: IRgan.ipynb  to extract input images from dataset for purposed GANs model.<br>
3)Run Main file: FinalEvaluation_Main.ipynb <br>

**please do not hesistate to share with me your constructive criticisms (Masoud.Moeini@Studium.uni-hamburg.de). 


**Paper Abstract:<br/>
**Recent innovations in Deep Learning (DL) and Convolutional Neural Networks (CNN) in computer vision have enabled us to develop sophisticated methods to improve traditional approaches. This paper presents a novel method to get a super-resolution version of images from low-scale images by applying a Genera- tive Adversarial Networks (GANs). The idea is that based on GANs we assume the input for the Generator network is sequences of low-scale images (8 × 8) and the Generator part generates high-scale images (32 × 32) with four times upscal- ing. For this purpose, the Generator network is trained with a synthetic loss function which consists of an adversarial loss and pixel-wise Mean Square Error (MSE) Loss. The adversarial loss leads the Generator network toward cre- ating the super-resolved images based on the Discriminator network learning ar- gument, that is trained to differentiate between real and fake images. The MSE loss function conceptually improves the performance of the Generator network, and in supervised approach, computes the error between the generated super- resolved images and the original images as a ground truth. Code is available at: https://github.com/MasoudMoeini/Computer-Vison 
<br/>

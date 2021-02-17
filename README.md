# Resolution Refinement for Enlarged Scale Images Using GANs
Click on:<br/>
**- FinalEvaluation_Main.ipynb** file to see prediction model with GANs(two stream of CNN using tensorflow) and visulization.
<br/>
<br/>
If you are Intereseted to run the repository locally in your pc, make sure that you have already installed  jupyter nootbook and necessary python libraries. <br/>
1) Clone repository (Reference dataset [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) has already been downloaded and accommodated in repository) <br/>
2) Run file: **[IRgans.ipynb](https://github.com/MasoudMoeini/Computer-Vison/blob/master/IRgans.ipynb)**  to extract input images from encoded data set for GANs model.<br>
3) Run Main file: **[FinalEvaluation_Main.ipynb](https://github.com/MasoudMoeini/Computer-Vison/blob/master/FinalEvaluation_Main.ipynb)**<br>

**please do not hesistate to share with me your constructive criticisms "Masoud.Moeini@Studium.uni-hamburg.de".** 


# Paper Abstract:<br/>
*Recent innovations in Deep Learning (DL) and Convolutional Neural Networks (CNN) in computer vision have enabled us to develop sophisticated methods to improve traditional approaches. This paper presents a novel method to get a super-resolution version of images from low-scale images by applying a Generative Adversarial Networks (GANs). The idea is that based on GANs we assume the input for the Generator network is sequences of low-scale images (8 × 8) and the Generator part generates high-scale images (32 × 32) with four times upscaling. For this purpose, the Generator network is trained with a synthetic loss function which consists of an adversarial loss and pixel-wise Mean Square Error (MSE) Loss. The adversarial loss leads the Generator network toward creating the super-resolved images based on the Discriminator network learning argument, that is trained to differentiate between real and fake images. The MSE loss function conceptually improves the performance of the Generator network, and in supervised approach, computes the error between the generated super-resolved images and the original images as a ground truth. Code is available at: https://github.com/MasoudMoeini/Computer-Vison* 
<br/>
<img width="816" alt="Screenshot 2021-02-04 at 12 41 35" src="https://user-images.githubusercontent.com/43514418/106888138-6f416500-66e6-11eb-9b11-ed89f151be29.png">
<br/>
<img width="756" alt="Screenshot 2021-02-04 at 12 41 56" src="https://user-images.githubusercontent.com/43514418/106888583-0c9c9900-66e7-11eb-8554-8b09d71c0a7c.png">
<br/>
<img width="629" alt="Screenshot 2021-02-04 at 12 52 21" src="https://user-images.githubusercontent.com/43514418/106889218-fcd18480-66e7-11eb-9934-a753fada5708.png">
<br/>
<img width="575" alt="Screenshot 2021-02-04 at 12 52 43" src="https://user-images.githubusercontent.com/43514418/106889219-fd6a1b00-66e7-11eb-8f25-462582d73695.png">
<br/>
<img width="815" alt="Screenshot 2021-02-04 at 13 17 51" src="https://user-images.githubusercontent.com/43514418/106891818-859def80-66eb-11eb-85a8-71f318f9773a.png">

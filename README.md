# Computer-vision-projects

In this repository I am sharing my **codes** for some projects and assignments of **the graduate level courses (Intro to computer vision, deep learning and computer vision)** I took during my PhD.

I hope you find it useful! :-)

You can use the link in each project to directly open and run the codes in google colab. Note that you should upload the files provided in the data path of each project. 

## Overview

### Projects

<table style="width:100%">
  <tr>
    <th>
      <p align="center">
           <a> <img src="./Convolution/img/sobel.png" alt="Overview" width="80%" height="80%"></a>
           <br>1: Convolution
           <br><a href="./Convolution" name="convolution_code">(code)</a>
      </p>
    </th>
        <th><p align="center">
           <a><img src="./Image%20segmentation%20with%20k-means/img/segmented_image.png" alt="Overview" width="80%" height="80%"></a>
           <br>2: Image segmentation with k-means
           <br><a href="./Image%20segmentation%20with%20k-means/" name="kmeans_code">(code)</a>
        </p>
    </th>
      </th>
        <th><p align="center">
           <a> <img src="./GMM/img/gmm_anim.gif" alt="Overview" width="80%" height="80%"></a>
           <br> 3: Gaussian mixture model (GMM) Clustering
           <br><a href="./GMM/" name="GMM_code">(code)</a>
        </p>
    </th>
  </tr>
  <tr>
    <th>
      <p align="center">
           <a> <img src="./Transfer%20learning/img/transfer_image.JPG" alt="Overview" width="80%" height="80%"></a>
           <br>4: Transfer learning
           <br><a href="./Transfer%20learning" name="transfer_code">(code)</a>
      </p>
    </th>    
  <th>
      <p align="center">
           <a> <img src="./Grad-CAM%20saliency%20maps/img/gradcam_output.png" alt="Overview" width="80%" height="80%"></a>
           <br>5: Grad-CAM saliency maps
           <br><a href="./Grad-CAM%20saliency%20maps" name="gradcam_code">(code)</a>
      </p>
    </th>    
    <th>
      <p align="center">
           <a> <img src="./Generative%20adversarial%20networks/img/GAN_CNN.png" alt="Overview" width="80%" height="80%"></a>
           <br>6: Generative adversarial networks (GAN)
           <br><a href="./Generative%20adversarial%20networks" name="gan_code">(code)</a>
      </p>
    </th>    
  </tr>
  <tr>
    </tr>
 
  
</table>

--- 
## Table of Contents

#### [1 - Convolution](Convolution)
 - **Summary:** Implemented a simple 2D convolution operation. Implemented Gaussian, derivative of Gaussian, and Sobel filters without using OpenCV. Tested the code on some test images. 
 - **Keywords:** Convolution, Gaussian, Sobel
 
#### [2 - Image segmentation with k-means](Image%20segmentation%20with%20k-means)
 - **Summary:** Implemented k-means algorithm. Experimented with different k-values and iterations. Performed image segmentation on some test images.
 - **Keywords:** k-means, Image segmentation 

#### [3 - Gaussian mixture model (GMM) Clustering](GMM)
 - **Summary:** Implemented GMM algorithm. Experimented with different k-values and iterations. Performed image segmentation on some test images.
 - **Keywords:**  GMM, k-means, Image segmentation 

#### [4 - Transfer learning](Transfer%20learning)
 - **Summary:** Experimented transfer learning with a pretrained CNN (InceptionResNetV2) and a sub-network of it to perform classification on an image dataset. Visualized the filters in the first layer. Implemented image augmentation.
 - **Keywords:**  Keras, Image augmentation, Transfer learning, Pre-trained network, CNN

#### [5 - Class-discriminative saliency maps using Grad-CAM](Grad-CAM%20saliency%20maps)
 - **Summary:** Implemented the original Grad-CAM paper with a pretrained VGG-16 model. Visualized the results and their respective predicted class on the different test cases with a short discussion. 
 - **Keywords:**  Keras, Gradient flow, Saliency maps, Grad-CAM, CNN
 
 #### [6 - Generative adversarial networks (GAN)](Generative%20adversarial%20networks)
 - **Summary:** Built two GAN models, one with Dense layers and the other with convolutinal layers and compared their performance on Fashion MNIST data. 
 - **Keywords:**  Keras, Dense GAN, Convolutional GAN

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
           <a> <img src="./Convolution/img/sobel.png" alt="Overview" width="60%" height="60%"></a>
           <br>1: Convolution
           <br><a href="./Convolution" name="convolution_code">(code)</a>
      </p>
    </th>
        <th><p align="center">
           <a><img src="./Image%20segmentation%20with%20k-means/img/segmented_image.png" alt="Overview" width="60%" height="60%"></a>
           <br>2: Image segmentation with k-means
           <br><a href="./Image%20segmentation%20with%20k-means/" name="kmeans_code">(code)</a>
        </p>
    </th>
      </th>
        <th><p align="center">
           <a><img src="./GMM/img/segmented_image_gmm.png" alt="Overview" width="60%" height="60%"></a>
           <a><img src="./GMM/img/gmm_anim.gif" alt="Overview" width="40%" height="40%"></a>
           <br> 3: Gaussian mixture model (GMM) Clustering
           <br><a href="./GMM/" name="GMM_code">(code)</a>
        </p>
    </th>
  </tr>
  <tr>
    <th>
      <p align="center">
           <a> <img src="./Transfer%20learning/img/transferModel.png" alt="Overview" width="60%" height="60%"></a>
           <br>4: Transfer learning
           <br><a href="./Transfer%20learning" name="transfer_code">(code)</a>
      </p>
    </th>    

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
 - **Keywords:**  Keras, Image augmentation, Transfer learning, Pre-trained network
 

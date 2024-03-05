# ModaLink
Place recognition is an important task for robots and autonomous cars to localize themselves and close loops. While single-modal sensor-based methods have have shown satisfactory performance, cross-modal place recognition that retrieving images from a point-cloud database remains a challenging problem. 
Current cross-modal methods transform images into 3D points using depth estimation for modality conversion, which are usually computationally intensive and need expensive labeled data for depth supervision. 
In this work, we introduce a fast and lightweight framework to encode images and point clouds into place-distinctive descriptors. We propose an effective Field of View (FoV) transformation module to convert point clouds into an analogous modality as images.
This module eliminates the necessity for depth estimation and helps subsequent modules achieve real-time performance. We further design a non-negative factorization-based encoder to extract mutually consistent semantic features between point clouds and images. This encoder yields more distinctive global descriptors for retrieval. Experimental results on the KITTI dataset show that our proposed methods achieve state-of-the-art performance while running in real-time. Additional evaluation on a self-collected dataset covering a 17 km trajectory further shows the practical generalization capabilities. We have released the implementation of our methods as open source at: https://github.com/SpadyDong/ModaLink.git.
## ModaLink: Unifying Modalities for Efficient Image-to-PointCloud Place Recognition
![schema](https://github.com/SpadyDong/I2P-V2/assets/47657625/0e5b7afd-c8e3-49a6-bbae-bf50693bd95b)

## Table of Contents

## Dependencies

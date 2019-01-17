# unreal2kinect
Dataset for use with [CycleGAN](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) to convert images from Unreal Engine into kinect-like images and vice-versa

# Changes in WithProps Sequence:

* Updated to most recent RobCoG kitchen, primarily for the warmer lighting

* Added more props in more arbitrary locations, hopefully breaking up some of the rectangular shapes of the kitchen

* Added long, "bland" sequence of images in order to prevent the GAN from learning the kitchen environment specifically

* Increased number of images

# Sources

**Kinect dataset source:**
Category Modeling from just a Single Labeling: Use Depth Information to Guide the Learning of 2D Models
Quanshi Zhang, Xuan Song, Xiaowei Shao, Huijing Zhao, and Ryosuke Shibasaki

https://sites.google.com/site/quanshizhang/dataset

**Unreal dataset made with assets from:**
https://github.com/robcog-iai/RobCoG

# 4cus
It will help you focus when working

Introduction
My work can be divided into two parts: label data and
object detection. Image labeling and object detection are
fundamental tasks in the field of computer vision, enabling
applications such as autonomous driving, surveillance, and
image recognition. 

Technical Overview
To ensure the reliability and quality
of our labeled dataset, I employed a camera to capture
images and utilized the labelImage tool developed by
Tzutalin for precise annotation. This meticulous labeling
process serves as a solid foundation for subsequent analysis
and modeling.
For object detection, I integrated the resnet 50
v2 model from tensorzoo, a state-of-the-art pre-trained
model renowned for its exceptional performance in object
detection tasks. By leveraging the capabilities of this
model, I aimed to accurately identify and classify
objects within our labeled images, streamlining the
detection process and saving valuable time and resources.

How to Install
I'd recommend you to install the .ipynb file on jupyter notebook or gg colab, you can run just like me. Hwever, some version may not be compatible for each other or you may don't have some library. You may just easily use pip install ... One mor thing, I can run this on window 10, 11 and python 3.10, some othr OS may need to change some. Hope you can do it!

Usage section
I use tensorflow 2.10.0 version, CUDA 11.2 and CuDNN 8.1. If you see some problem about DNN, CNN or OS, it maybe because you didn't install right. You can see this page to check what versions https://www.tensorflow.org/install/source_windows are good together.



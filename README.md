# Histopathology-Stain-Color-Normalization
Deep Convolutional Gaussian Mixture Model for Stain-Color Normalization in Histopathological H&amp;E Images

## Overview ##

Stain-color variation degrades the performance of the computer-aided diagnosis (CAD) systems. In the presence of severe color variarion between training set and test set in histopathological images, current CAD systems including deep learning models suffer from such an undesirable effect. Stain-color normalization is known as a remedy.

![alt text](https://github.com/FarhadZanjani/Histopathology-Stain-Color-Normalization/blob/master/Color_Normalization.png)

## Methodology ##
Stain-color normalization model can be defined as a generative models that by applying on input image can create different color copies of input image to somehow the converted image contain specific chromatic distribution. Our proposed method contains two stage: (1) fitting a Gaussian mixture model (GMM) by considering the shape and apearance of image content structures. To do so the visual representation and modeling of convolutional neyral networks (CNNs) are exploited. (2) transforming the estimated distribution to any arbitary distribution that computed from a secondary (template) image.

## Citation ##
Zanjani F. G., Zinger S., de With P. H.N., ...

## Results ##
Zanjani F. G., Zinger S., de With P. H.N., ...





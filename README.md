# Reconstructing Seen Images from Visually Evoked fMRI using a Promoted Shape-Semantic GAN
<p align="center">
<img width="471" alt="image" src="https://github.com/shamimgolafshan/Reconstructing-Seen-Images/assets/35660420/e65ad1a2-d2bc-45d2-8e3b-88e2aa95f92b">
</p>

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Method](#method)
- [Results](#results)
- [Citation](#citation)

## Introduction

This project focuses on reconstructing perceptual images from fMRI data using a promoted Shape-Semantic GAN. Our approach improves the quality of reconstructed images, providing a more accurate representation of the images seen by subjects during the experiment.

## Data

We used preprocessed data from the study "Reconstructing Perceptive Images from Brain Activity by Shape-Semantic GAN"[1]. The preprocessed fMRI data can be downloaded from the following link: [Preprocessed fMRI Data](https://figshare.com/articles/dataset/Deep_Image_Reconstruction/7033577).

## Method

We utilized a Convolutional Autoencoder to decode the best features of naturalistic images and then trained base decoders using these features. Below is an overview of our framework:

![Framework Overview](path/to/your/framework-image.png)

## Results

As a result, we achieved the following reconstructions:

![Resulting Images](https://github.com/shamimgolafshan/Reconstructing-Seen-Images/assets/35660420/8dd881fc-3638-4624-8e24-82ba06e08017)


## Citation

If you use this project in your research, please cite the following articles:

1. Fang, Tao, Yu Qi, and Gang Pan. "Reconstructing perceptive images from brain activity by shape-semantic gan." Advances in Neural Information Processing Systems 33 (2020): 13038-13048.
2. Shen, Horikawa, Majima, and Kamitani (2019) Deep image reconstruction from human brain activity. PLoS Comput. Biol. http://dx.doi.org/10.1371/journal.pcbi.1006633.


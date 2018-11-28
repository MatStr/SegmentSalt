# SegmentSalt
Neural network as image segmentation model.
This repository contains a jupyter notebook that was used for the Kaggle competition "TGS Salt Identification Challenge".
The problem statement for this competition was to identify regions that contain salt in seismic images - a typical segmentation problem. In addition to the seismic image (101x101 greyscale) the "depth" of the taken image was given. I decided to design a U-Net model. Instead of rescaling the images such that the original implementation of the the U-Net (and the pretrained weights) is applicable, I decided to start from scratch. The reason for that is that I wanted to make use of the "depth" as an additional feature.

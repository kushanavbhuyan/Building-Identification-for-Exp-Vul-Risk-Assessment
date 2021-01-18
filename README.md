# Deep Learning to Foster Building Detection 
## This repository will be an on-going hub for my master thesis codes regarding the detection and characterisation of building elements-at-risk. Will be updating it every week or so with more codes and pre-processing updates.
## Stat-update: 0.2

### U-Net 

This architecture is based on the famous work of Olaf Ronnerberg called [U-Net](https://arxiv.org/abs/1505.04597). The architecture consists of:

1. Conv2D – Simple convolutional layer with a 3x3 kernel. 
2. MaxPooling2D – Simple max pooling with a 2x2 kernel. 
3. Cropping2D – Cropping layer to crop features and concatenate 
4. Concatenate layer that concatenates multiple feature maps from different stages of training. 
5. UpSampling2D – To increase the size of the feature map. 
6. SoftMax layer that generates a final segmentation map. 

![picture](https://drive.google.com/uc?export=view&id=1XhUD2J0evs9kP3PyBl4BPy86oUOCwQO8)

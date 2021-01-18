
# Deep Learning to Foster Building Footprint Detection 

Stat-update: 0.2

This repository is an on-going hub for my master thesis materials and codes regarding the detection and characterisation of building elements-at-risk. Will be updating it every other week or so with more codes, materials, data and pre-processing updates.

### Information about buildings is, sufficed to say, a very important aspect not just for urban land registry or transportation but also for disaster/hazard risk assessment. Specifically, typological attributes of buildings like number of residents living in them, number of floors, and many more. The MSc Thesis Research aims at figuring out the typological attributes of the buildings by incorporating deep learning and other proxy information as a means of detecting and characterising the buildings.


## Deep Learning Networks: U-Net and ResUnet 

U-Net architecture is based on the famous work of Olaf Ronnerberg called [U-Net](https://arxiv.org/abs/1505.04597). The architecture consists of:

1. Conv2D – Simple convolutional layer with a 3x3 kernel. 
2. MaxPooling2D – Simple max pooling with a 2x2 kernel. 
3. Cropping2D – Cropping layer to crop features and concatenate 
4. Concatenate layer that concatenates multiple feature maps from different stages of training. 
5. UpSampling2D – To increase the size of the feature map. 
6. SoftMax layer that generates a final segmentation map. 

![picture](https://drive.google.com/uc?export=view&id=1XhUD2J0evs9kP3PyBl4BPy86oUOCwQO8)


## Deep Learning Networks: ResUnet
### ResUNet, a semantic segmentation model inspired by the deep residual learning and UNet. An architecture that take advantages from both (Residual and UNet) models.

Advantages:
1. The residual unit will ease the training of the network.
2. The skip connections within a residual unit and between low levels and high levels of the network will facilitate information propagation without degradation,making it possible to design a neural network with much fewer parameters.








# Deep Learning to Foster Building Footprint Detection 

## Deep Learning Networks: U-Net 

U-Net architecture is based on the famous work of Olaf Ronnerberg called [U-Net](https://arxiv.org/abs/1505.04597). The architecture consists of:

1. Conv2D – Simple convolutional layer with a 3x3 kernel. 
2. MaxPooling2D – Simple max pooling with a 2x2 kernel. 
3. Cropping2D – Cropping layer to crop features and concatenate 
4. Concatenate layer that concatenates multiple feature maps from different stages of training. 
5. UpSampling2D – To increase the size of the feature map. 
6. SoftMax layer that generates a final segmentation map. 


## Deep Learning Networks: ResUnet
### ResUNet, a semantic segmentation model inspired by the deep residual learning and UNet. An architecture that take advantages from both (Residual and UNet) models.

Paper: https://arxiv.org/pdf/1711.10684.pdf

Advantages:
1. The residual unit will ease the training of the network.
2. The skip connections within a residual unit and between low levels and high levels of the network will facilitate information propagation without degradation,making it possible to design a neural network with much fewer parameters.


#### Prediction algorithm credits: [Ashok Dahal](https://github.com/ashokdahal). Please check his amazing work as well !!




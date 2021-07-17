# Image-Segmentation-using-Unet
Hello, this python deep learning project consists of a U net trained model which is trained on nuclei images.
This U net architecture is actually a highly refered architecture for Image segmentation. Here I did semantic image segementation, highlighting the nuclei of the cells.
![image](https://user-images.githubusercontent.com/58435489/126040663-4a2e39b0-d000-44dc-b6df-9c2711211452.png)

As you can see, image provides the visual architecture of the neural network. 
The UNET was developed by Olaf Ronneberger et al. for Bio Medical Image Segmentation. The architecture contains two paths. First path is the contraction path (also called as the encoder) which is used to capture the context in the image. The encoder is just a traditional stack of convolutional and max pooling layers. The second path is the symmetric expanding path (also called as the decoder) which is used to enable precise localization using transposed convolutions. Thus it is an end-to-end fully convolutional network (FCN), i.e. it only contains Convolutional layers and does not contain any Dense layer because of which it can accept image of any size.

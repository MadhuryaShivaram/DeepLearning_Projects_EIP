print(score)  -  0.9912

Convolution - is the process of obtaining significant pixels (features) of an image using a filter of required size. This is done by a matrix operation between input image and the filter.

Filters/Kernels - is a matrix used to extract features and produce feature maps of an image

Epochs - is the number of times we iterate over the training data set inorder to obtain all the significant features.

1x1 Convolution - is the process of convolving an image with 1*1 filter . This helps us in reducing the number of channels in an image.

3x3 Convolution - is a process of obtaining significant pixels (features) of an image using a filter of size 3 * 3

Feature Maps - are a group of features which are extracted froma an image using the kernel.

Activation Function - is a function that helps us retain the prominent pixels of a feature map.

Receptive Field - tells us how many pixels is a layer aware of. Global receptive field exists only for the last layer of a network and should be equal to size of an object.

# Image_Classification_CNN_PyTorch
MNIST handwritten digits dataset 

Before we start off with building a CNN model for image classification using PyTorch, here is a brief description of MNIST handwritten digits dataset. We have handwritten digits collected from various scanned documents and similar sources with each image being 28 by 28 pixel square. The challenge is to classify those handwritten digits into either of 10 digit classes - 0 to 9. Training set has 60000 images and testing set has 10000 images. 

*the .ipynb file which has the pytorch code has been made quite explanatory with the underlying assumption that reader has knowledge of concepts like convolution, pooling,full connected layers, dropout etc. Hence, here are a few highlights about this article: 

->Dataset API under torchvision has not been used. Instead, data has been loaded on google drive and a custom function has been built to pull dataset into a google collab environment. 

->Again Dataset APIs have not been used for MNIST data transformations like Rescaling. Custom functionality has been added. 

->Scope of Improvement: Hyperparameters like optimizer, learning rate can be changed. Besides,normalization transformation too can be applied which is not implemented above. 

*The following CNN architecture has been used. 

<img width="962" alt="Screen Shot 2020-11-08 at 11 59 04 PM" src="https://user-images.githubusercontent.com/56598403/98508638-d194e180-222d-11eb-9bce-d993ec4bea30.png">

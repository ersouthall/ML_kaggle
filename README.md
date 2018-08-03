Repository for Kaggle Competition https://www.kaggle.com/c/data-science-bowl-2018 -- Data Science Bowl 2018

Use of Multi-layer perceptron classifier (MLP) and Convolutional neural network (CNN). To avoid losing spatial information on images during reshaping and implementing a pixelwise MLP, split all raw images into 256 subimages (of lower dimension). 


Tools used:
- Keras
- stochastic gradient decent optimizer 'Adam'
- Various batch sizes and hidden layers
- Dropout layers to avoid overfitting
- ReLU activation on final fully connected layer with a logistic activation function 
- Maxpooling layers to downsample
- Deconvolution layer to upsample the images
- U-Net model (26 convolutional layers with maxpooling and concatenate layers and ReLU) 
- Extended U-Net with batch normalization, gives a higher performance

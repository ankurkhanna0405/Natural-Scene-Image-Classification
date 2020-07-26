# Natural-Scene-Image-Classification
Machine Learning and Computer Vision Project



<H3>ABSTRACT</H3>
Identifying natural scenes from all around the world is an interesting computer vision problem. In this project, we are going to classify six different categories of images (buildings, forest, glacier, mountain, sea, street). A simple architecture of Convolutional Neural Networks is employed to classify the images in the dataset Natural scene image classification. 
We use the deep learning library Keras with a TensorFlow backend and a basic CNN Sequential model as it allows us to easily stack sequential layers (and even recurrent layers) of the network in order from input to output. Moreover, we use "Adam" optimization algorithm to train the parameters of the model and "sparse categorical cross entropy" for loss function, as both of these are good for this multi-class classification. We applied the nonlinear ReLu activation function for inner Convolutional layers and Softmax activation function  for the output layer.
With around 40 epochs (each epoch comprising of one forward pass and backward pass) we managed to attain an accuracy of 93% by training the model and an accuracy of 83% on the test set.

<H3> DATASET</H3>
This is image dataset is of Natural Scenes around the world and is named as “Intel Image Classification”. This Data contains around 25k images of size 150x150 distributed under 6 categories: {'buildings' -> 0, 'forest' -> 1, 'glacier' -> 2, 'mountain' -> 3, 'sea' -> 4, 'street' -> 5}. The Train, Test and Prediction data is separated in different files. There are around 14k images in Train, 3k in Test and 7k in Prediction. Fraction of the training data is used as validation data. The model will set apart this fraction of the training data, will not train on it, and will evaluate the loss and any model metrics on this data at the end of each epoch. Therefore, while training the model we use 30% of the Train set i.e. around 4k images as Cross Validation set and rest for Training set. 
To download the Dataset please goto following link : https://www.kaggle.com/prasunroy/natural-images

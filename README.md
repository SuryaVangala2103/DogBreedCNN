# DogBreedCNN

CNN used to classify dogs based on Kaggle Dataset: https://www.kaggle.com/gpiosenka/70-dog-breedsimage-data-set

First, Dataset class was made to split csv from dataset and convert into labels and data for training and test datasets

Then, standard CNN was attempted, with poor results (4% accuracy 3 epochs)

Then, implemented ResNet (https://github.com/Kulbear/deep-learning-coursera/blob/master/Convolutional%20Neural%20Networks/Residual%20Networks%20-%20v1.ipynb)

23% accuracy after 3 epochs, 99% accuracy after 10 epochs

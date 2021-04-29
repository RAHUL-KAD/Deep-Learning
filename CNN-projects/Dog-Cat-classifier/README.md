
# Dog/Cat Classifier

## 1. Problem Statement:

I wanted to use CNN to predict the given image is cat or dog, so I used dataset provided on ![kaggle](https://www.kaggle.com/tongpython/cat-and-dog).

## 2. Data Preprocessing:

To process a image data for eg, to rescale, zoom, flip and to load train and test dataset I used ImageDataGenerator from Keras library.

I rescaled the values between 0 and 1 with zoom range 0.2 and horizontal flip as True. 

The size of the image is (64, 64) pixcels with batch size 32 and class mode as **binary**

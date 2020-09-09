
## Multi-Instance Learning on MNIST Dataset

### Problem
  - Classification of MNIST data. 

### Approach Used
  - Download and normalize the input in dataset. 
  - Convert to binary encoding - either 0 or 1. 
  - Build the train and test sets. 
  - Embed the dataset with zeroes around the actual image to increase the size of the image.
  - Build Fully Convolutional Network and train the model on preprocessed data.
  - Get the training and test accuraries, errors.

### Dataset
  - MNIST data consisting of numbers from 0 - 9 is used from keras Library.
  - Each Image is 72x72 pixels. 
  - Bags of data is formed. Bags are labelled 1 and 0.
  - If the bag contains a 0, it's labelled 0, else 1.

# Convolutional-Neural-Networks---Plant-Seedlings-Image-Classification-using-CNNs-in-Keras

## Project Description

### Data Description:

From the outset we are provided with a dataset of images of plant seedlings at various stages of growtth. Each image has a filename that is its
unique id. The dataset comprises of 12 plant species. The goal of the project is to create a classifier capable of determining a plant's
species from a photo.

### Dataset:

The dataset can be download from this repository.
The data file names are:

    images.npy

    Label.csv

### Steps and tasks:

1. Import the libraries, load dataset, print shape of data, visualize the images in dataset. 

2. Data Pre-processing:

    a. Normalization.

    b. Gaussian Blurring.
  
    c. Visualize data after pre-processing.
  
3. Make data compatible: (10 Marks)

    a. Convert labels to one-hot-vectors.

    b. Print the label for y_train[0].

    c. Split the dataset into training, testing, and validation set.

    d. Check the shape of data, Reshape data into shapes compatible with Keras models if it’s not already. If it’s
       already in the compatible shape, then comment in the notebook that it’s already in compatible shape.
     
4. Building CNN:

    a. Define layers.

    b. Set optimizer and loss function. (Use Adam optimizer and categorical crossentropy.
  
5. Fit and evaluate model and print confusion matrix.

6. Visualize predictions for x_test[2], x_test[3], x_test[33], x_test[36], x_test[59].


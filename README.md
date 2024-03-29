# CAIS-Winter-Project
### Daniel Yang dyang990@usc.edu

### Description
#### In this project "Muffin vs. Chihuahua," I applied the VGG-16 pre-trained convolutional neural network, a 16-layer deep architecture trained on ImageNet. The goal was to classify images of blueberry muffins and Chihuahuas, using a dataset that included 4733 training images and 1184 test images for binary classification.

### Dataset
#### The code utilizes a dataset comprising images of blueberry muffins and Chihuahuas, organized into training and test sets. As part of the preprocessing steps, I loaded the images, resized them to dimensions of (224, 224) pixels, and normalized their pixel values using the preprocess_input function from the VGG-16 model, essential to guarantee that the images are in a suitable format for input into the neural network.

### Model Development and Training
#### I chose the model VGG-16, a pre-trained convolutional neural network. I initialized the model during the training process and made predictions on a sample of 25 test images. 

### Results
#### I achieved a final accuracy score of 78%.

### Discussion
#### The dataset I used fits the task at hand in terms of providing the correct classifications. This can be extended to other implications in using computer vision binary classification for other examples. 

# Flower-Recognization
[README](bharatc9530/Flower-Recognization/data_files)
# All Data Stored in flowers folder.
# All csv files of training and testing data, model is stored with its weight in folder data_files.

### Use CNN architecture I got an Accuracy Of 81% on training Data and 79% on testing Data


#### Context
This dataset contains 4242 images of flowers.
The data collection is based on the data flicr, google images, yandex images.
You can use this datastet to recognize plants from the photo.

#### Content
The pictures are divided into five classes: daisy, tulip, rose, sunflower, dandelion.
For each class there are about 800 photos. Photos are not high resolution, about 320x240 pixels. Photos are reduced to a single size of (150,150,3), they have same proportions!

### Uses Generator
A generator is a function that behaves like an iterator. An iterator loops (iterates) through elements of an object, like items in a list or keys in a dictionary. A generator is often used like an array.
It does'nt hold result in memory but it take longer to process. It has major advance that it does'nt consumer more memory so, less chances of getting out of memory error.
### Uses Two method 
#### In First method I have created the Generator
#### In Second method I use the keras Generator

#### Applied Data Augmentation
In order to avoid overfitting problem, we need to expand artificially our dataset. We can make your existing dataset even larger. The idea is to alter the training data with small transformations to reproduce the variations.

Approaches that alter the training data in ways that change the array representation while keeping the label the same are known as data augmentation techniques. Some popular augmentations people use are grayscales, horizontal flips, vertical flips, random crops, color jitters, translations, rotations, and much more.

By applying just a couple of these transformations to our training data, we can easily double or triple the number of training examples and create a very robust model.

#### Applied CONVOLUTIONAL NEURAL NETWORKS 
A Convolutional Neural Network is a special type of an Artificial Intelligence implementation which uses a special mathematical matrix manipulation called the convolution operation to process data from the images.

#### Model Performance Visualization Using Seaborn library
loss function of training and validation data.
accuracy function of training and validation data.

#### Model Architecture Visualization
using netron library to visualize neural network architecture in detail.

#### Model saving 
saving model architecture as well as model weights. it is stored in data_files along with csv file of detail about training and testing.

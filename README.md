# Street-View-House-Numbers-SVHN-Classification
Neural networks classifiers are developed for the Street View House Numbers dataset 




Context
Object recognition and image processing has become one of the hottest topics in machine learning due to its vast and creative potential applications in the real world. The ability to process visual information using machine learning algorithms can be very useful, such as measuring the quality of NYC Bike Lanes through street imagery. Within this field, the Street View House Numbers (SVHN) dataset is one of the most popular ones. It has been used in neural networks created by Google to read house numbers and match them to their geolocations. This is a great benchmark dataset to play with, learn and train models that accurately identify street numbers, and incorporate into all sorts of projects.

Content
This dataset contains three .zip files that contain over 600k labelled real-world images of house numbers taken from Google Street View. The sequence of numbers in the images are of bounded length.

test.zip: 26,032 digits for testing
train.zip: 73,257 digits for training
extra.zip: 531,131 additional, somewhat less difficult samples, to use as extra training data
Additional Notes

There are 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10.
The images are the original, variable-resolution, color house-number images with character level bounding boxes in .png format.
digitStruct.mat: Contains bounding box information for each respective .zip file are stored as digitStruct.mat, which can be loaded using Matlab. The digitStruct.mat files contain a struct called digitStruct with the same length as the number of original images.
Each element in digitStruct has the following fields:
name: string containing the filename of the corresponding image
bbox: struct array that contains the position, size and label of each digit bounding box in the image. Ex. digitStruct(300).bbox(2).height gives height of the 2nd digit bounding box in the 300th image.
Acknowledgements
The SVHN dataset originates from http://ufldl.stanford.edu/housenumbers/. The banner photo was by Annie Spratt on Unsplash.

The original paper that introduces and examines this data:

Yuval Netzer, Tao Wang, Adam Coates, Alessandro Bissacco, Bo Wu, Andrew Y. Ng Reading Digits in Natural Images with Unsupervised Feature Learning NIPS Workshop on Deep Learning and Unsupervised Feature Learning 2011.

Inspiration & Resources
Given the testing and training data, can you train a model (try Keras and/or TensorFlow) that accurately identifies house numbers in an image (with difficulties like picture brightness, blurriness)?
What are some interesting datasets that can be merged with object detection datasets like this to form new applications?
Additional resources are Getting Started with SVHN Dataset and Ji Yan's project that aims to tackle the SHVN dataset using Convolutional Network in Tensorflow.

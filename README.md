# Street-View-House-Numbers-SVHN-Classification


### Objective
Image recognition is one of the hottest topics in machine learning. In this project, the popular dataset __Street View House Numbers(SVHN)__ by Google is used as the input. We will build neural networks based classifiers for the task of digit prediction.


### Data Content 
The dataset has three .zip files that contain over 600k well-labeld real-world images of house numbers taken from Google Street View. 
test.zip: 26,032 digits for testing
train.zip: 73,257 digits for training
extra.zip: 531,131 additional, somewhat less difficult samples, to use as extra training data

Additional Information

There are 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10.
The images are the original, variable-resolution, color house-number images with character level bounding boxes in .png format.
digitStruct.mat: Contains bounding box information for each respective .zip file are stored as digitStruct.mat, which can be loaded using Matlab. The digitStruct.mat files contain a struct called digitStruct with the same length as the number of original images.
Each element in digitStruct has the following fields:
name: string containing the filename of the corresponding image
bbox: struct array that contains the position, size and label of each digit bounding box in the image. Ex. digitStruct(300).bbox(2).height gives height of the 2nd digit bounding box in the 300th image.

Acknowledgements
The SVHN dataset originates from http://ufldl.stanford.edu/housenumbers/. 

The original paper that introduces and examines this data:

Yuval Netzer, Tao Wang, Adam Coates, Alessandro Bissacco, Bo Wu, Andrew Y. Ng Reading Digits in Natural Images with Unsupervised Feature Learning NIPS Workshop on Deep Learning and Unsupervised Feature Learning 2011.

# Street-View-House-Numbers-SVHN-Classification


### Objective
Image recognition is one of the hottest topics in machine learning. In this project, the popular dataset __Street View House Numbers(SVHN)__ by Google is used as the input. We will build neural networks based classifiers for the task of digit prediction.


### Data Content 
The dataset has three .zip files that contain over 600k well-labeld real-world images of house numbers taken from Google Street View. 
-test.zip: 26,032 digits for testing
-train.zip: 73,257 digits for training
-extra.zip: 531,131 additional data might come in handy

### Additional Information
There are 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10. <br>
The images are the original, variable-resolution, color house-number images with character level bounding boxes in .png format.<br> 
digitStruct.mat: Contains bounding box information for each respective<br>
Each element in digitStruct has the following fields:
name: string containing the filename of the corresponding image
bbox: struct array that contains the position, size and label of each digit

### Acknowledgements
The SVHN dataset orginal source: http://ufldl.stanford.edu/housenumbers/. 


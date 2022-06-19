# Cloud_Classifier
An image classifier and inference deployment for classifying cloud type from the 10 main types.

The cloud_learner uses a collection of images downloaded from the web to train a neural network with the 10 main cloud types:
* Cirrus
* Cirrocumulus
* Cirrostratus
* Altocumulus
* Altostatus
* Nimbostratus
* Stratocumulus
* Stratus
* Cumulus
* Cumulonimbus

The neural network is pre-trained with resnet34. This speeds up the learning proccess. 

The model has a error rate of 0.278 at present. It has the following confusion matrix:

![alt text1](data/confusion_matrix.PNG?raw=true "Confusion matrix for model")


Example webapp cloud type classifier.

![alt text2](data/cloud_demo.PNG?raw=true "Webapp example")


# DeepLearningTraining
Experiments with different deep learning architectures for image classification

## Dataset
xView (http://xviewdataset.org/) is a large publicly available object detection data set, with approximately 1
million objects across 60 categories. It contains manually annotated images from different scenes around the
world, acquired using the WorldView-3 satellite at 0.3m ground sample distance. There are 846 annotated
images in total. For this practice, we divide these annotations into 761 and 85 images for training and testing.
For image recognition, we crop previous images using their annotated bounding boxes to extract a subset of
objects of interest. In this way, we collected 21377 and 2635 objects for training and testing respectively. The
resulting images are resized to 224x224.

## Experiments
### 01 - ffNN 
Discuss and compare experiments using ffNNs, including optimization algorithm, number of layers /
parameters, and performance obtained with our models on the testing data set, including the plots
of the evolution of losses and accuracy performances.

### 02 - Regularization 
Refine previous ffNN architectures and optimize their parameters using regularization techniques to
prevent overfitting and enhance performance (e.g., augmentation, dropout, batch normalization, ...).

### 03 - CNN
Discuss and compare experiments using CNNs. Compare the performance obtained by
our own CNN architectures against different popular CNNs (e.g., AlexNet, VGG, ResNet, ...) trained
from scratch. 

### 04 - Transfer Learning
Compare previous results with popular architectures with the provided by their pre-trained versions
using transfer learning.

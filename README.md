# xray_classifier
X-ray Image Pneumonia Classification with Transfer Learning using ResNet-50/EfficientNetB0

This notebook implements a deep learning model using transfer learning with ResNet-50 for binary classification of X-ray images into "NORMAL" and "PNEUMONIA" categories. The notebook utilizes the TensorFlow framework and the Keras API.

The Pneumonia_Classifier.ipynb is done using ResNet50. I do not have the computational resources to use the model's full capabilities, Achieved an accuracy of 75.5%

The Pneumonia_Classifier_EfficientNet.ipynb is done using EfficientNetB0. Since the model is smaller and more efficient, it is easier to utilize its potential. Achieved an accuracy of **87.8%** with an implementation of class weights, learning rate scheduler, and early stopping to avoid overfitting.

Optimizations are still in progress...

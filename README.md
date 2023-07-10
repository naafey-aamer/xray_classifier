# xray_classifier
X-ray Image Pneumonia Classification with Transfer Learning using ResNet-50

This notebook implements a deep learning model using transfer learning with ResNet-50 for binary classification of X-ray images into "NORMAL" and "PNEUMONIA" categories. The notebook utilizes the TensorFlow framework and the Keras API.

We start by loading the pre-trained ResNet-50 model without its top fully connected layers.

Data generators are set up to preprocess the images by rescaling their pixel values.

The pre-trained layers of the ResNet-50 model can be either frozen or unfrozen based on the code provided. In this case, we keep the bottom layers frozen due to computational overhead, and new dense layers are added for binary classification.

The model is compiled with binary cross-entropy loss, SGD optimizer, and accuracy as the evaluation metric. A learning rate schedule and early stopping callback are defined for optimization.

Finally, the trained model is evaluated on the test set, and the test accuracy is printed.

Hyperparameter tuning for better performance is still in progress...

# Small-Image-Classification
Image Classification using ANN and CNN

This project is created using simple ANN and CNN implemented using TensorFlow.
The accuracy and F1 scores of both models were analysed and the CNN model was found to be more accurate than the ANN model.
The number of epochs and hidden layers have been deliberately reduced which has greatly affected accuracy of the model. This was done due to the excessive computation required for the dataset used.
The dataset used consists of 60000 samples of small images of various animals which are represented in 32x32x3 pixel grids.
It has been observed that the above model can be made much more accurate if processed using a GPU, if available rather than the CPU.
One hot encoding has also been used, thus the categorical cross entropy loss function has been used while implementing the neural network


# This is an ANN model to classify the 10 class MNIST dataset available at keras datasets
## 1. The model here is simple ANN with 2 Dense layers with Relu and Softmax as activations respectively. The 1st dense layer contains 125 neurons while the 2nd dense layer or the output layer contains 10 neurons (no of classes). The provision of dropout is given and the sparse_categorical_crossentropy is used as loss.
## 2. The loss and accuracy has been plotted with respective titles and axes names.
## 3. The dataset can directly be obtained from keras.datasets in form of tuple which make the task easier.
## 4. The training accuracy obtained is 98.73 % and the Validation accuracy obtained is 98.02 %.

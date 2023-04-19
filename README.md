# A-comprehensive-investigation-on-CIFAR10-CNN-Tensorflow-keras
This implementation builds a convolutional neural network to classify images in the CIFAR10 dataset, using 15% of the data for testing. The training duration is reported, and the accuracy and loss of the model are displayed for the training and validation data using a graph. Additionally, the prediction accuracy is reported on the test data.

Next, the performance of two different learning rate schedulers, Exponential and OneCycle, are compared over 50 epochs.

To examine the impact of the pooling layer on the network's accuracy and loss, the difference between using and not using it is studied over 50 epochs. The training duration, accuracy, and loss are reported.

Next, the effect of stride on the pooling layer is investigated by applying strides of 2 and 4 over 50 epochs, and the accuracy and loss are reported.

Finally, VGG 16 is used to classify the CIFAR10 dataset, with the all network's layers freezed for the first time and with one layer of it trainable for the second time. Accuracy and loss for both models are displayed in a single graph over 50 epochs.

Overall, this implementation includes various experiments that aim to improve image classification performance, exploring different network architectures, training techniques, and network properties. This code will be valuable for anyone interested in learning about deep learning and its application to image classification. The code is designed to facilitate easy replication of experiments and comparison of results.

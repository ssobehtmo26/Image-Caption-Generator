# Image Captioning

This repository contains an implementation of image captioning based on neural network (i.e. CNN + RNN). The model first extracts the image feature by CNN and then generates captions by RNN. CNN is VGG16 and RNN is a standard LSTM .

Normal Sampling and Beam Search were used to predict the caption of images.


# Network Topology:-

## Encoder
The Convolutional Neural Network(CNN) can be thought of as an encoder. The input image is given to CNN to extract the features. The last hidden state of the CNN is connected to the Decoder.
## Decoder
The Decoder is a Recurrent Neural Network(RNN) which does language modelling up to the word level. The first time step receives the encoded output from the encoder and also the <START> vector.


# Input
![input](https://user-images.githubusercontent.com/23000971/33495332-fbd2b75a-d6eb-11e7-999a-09fdc4255a6f.JPG)


# Output
![output](https://user-images.githubusercontent.com/23000971/33495366-2b5a9cd6-d6ec-11e7-9cd0-2b7adce57b3e.JPG)
![text](https://user-images.githubusercontent.com/23000971/33495435-7a9bd10c-d6ec-11e7-9b26-77c6865c0551.JPG)


# Dependencies

* Keras
* Theano 
* Numpy
* Pandas
* Matplotlib
* Pickle



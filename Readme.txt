APPLYING CNN TO MNIST DATA SET

To implement CNN this Model has two set of Neural networks Imported.

One of which is encoder and second one is decoder.

Encoder is basically four layered Convolutional Neural Network
and one extra layer to flatten the outputs.
the details our given in the image encoder.png

While Decoder is basically four layered Convolutional Neural Network
and one extra layer to Reshape the outputs to the original form for the final output.
the details our given in the image decoder.png

This Model is Trained on MNIST data set which contains black and white images of Numbers.
This model is used to first create an big image consisting of many numbers then decode it using convolutional filters. 
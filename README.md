# Vocal-Extraction-From-Audio

In this project I have created a CNN which contains convolutional and tanspose convolutional layers.
Convolution Layers will encode the input then Transpose Convolutinal layers will decode the vocal from
encoded features.

The interesting part was creating the dataset. For which what I did is as follow :-
  I took an instrumental video from youtube and divided it into 2 sec audio files.
  Then I took some audio clips which only contain vocals from a dataset on kaggle and did same thing as above.
  Then I mixed clips from instrumental part to the vocal and it was my input for model and the output of model I set was only the vocal without mixing.

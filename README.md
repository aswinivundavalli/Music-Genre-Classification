# Music-Genre-Classification
This project aims to model a classifier to classify songs into different genres using tensor flow library.



The project was written in 3 separate python codes:

Preprocess.py: Path to audio files is to be given as input. This python script calculates the MFCC and save the result in ‘.pp’ file

Formatinput.py: The script iterates over all ‘.pp’ files and generates ‘data’ and ‘labels’ that will be used as an input to the neural network.

Classifier.py: The script builds the neural  network and feeds it with ‘data’ and ‘labels’ and when it is done it will save ‘model.final’. This model accepts the test data and gives out the testing error.

Dataset used: http://opihi.cs.uvic.ca/sound/genres.tar.gz

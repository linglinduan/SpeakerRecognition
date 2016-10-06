# Speaker Recognition

Data comes from the LibriSpeech ASR corpus

http://www.openslr.org/12/

File: train-clean-100.tar.gz (6.3G)(training set of 100 hours "clean" speech) 

Converted flac files to wav files.

5 male speakers and 5 female speakers.

Female speakers: 1,3,5,7,9

Male speakers: 2,4,6,8,10

Neural Network built with PyBrain: 

Mean accuracy over 10 speakers: 

75% with 0.2 seconds of voice data (random guessing has 10% chance), 

95% with 2 seconds of data.

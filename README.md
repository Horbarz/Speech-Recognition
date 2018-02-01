# Project-IntroML
This is a simple speech recognition system implemented as the course project of Intro to Machine Learning.

We implemented a Hidden Markov Model here to model the time-varying process of producing speech using jupyter notebook. The program is written in Python and stored in the file named project_speech.ipynb. We recommend opening this file with jupyter notebook since those images added to explain the models and algorithms might not be shown correctly if the file is viewed on GitHub.

Dataset stores audio samples of spoken digit chains with varying length. We extract those only contain single digit and partition them samples in two groups, one for training and the other for validation, which are stored in two separate folders named train and test. We use 200 samples to train model for each digit and use around 30 samples for validation. One can load these samples using TRAIN.transcripts and TEST.transcripts. Those files contain words of digits spoken in the corresponding audio files specified by the name at the end of each line.

Validation using different number of states in the models is included in the code as well as results analysis.

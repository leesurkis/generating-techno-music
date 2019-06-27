
# Generating Techno Music using an LSTM

This purpose of this project is to train an LSTM neural network to generate techno midi files. The instrument choice is left to the discretion of the DJ or end user of the file, using Logic Pro or GarageBand.  

## Prerequisits

* Python 3.x
* Packages to be installed using pip:
	* Music21
	* Keras
	* Tensorflow
	* h5py

## The data
The model in this project was trained on 38 techno midi files downloaded from http://www.partnersinrhyme.com/midi/Dance_Techno/

## Training the model

* Please see the **training.py** file to train the LSTM on the midi files. Midi files saved in ./midi_songs can be replaced with other genres of music. 
* Works best with one instrument but can be run multiple times to generate different midi files for different instruments. 

## Generating music

* Please see **predict.py** to generate techno midi files
* Weights will be saved after each epoch so model can be stopped when you are satisfied with the loss

Please see the full blog post here and view a pdf of my slides here. 

## References

https://medium.com/artists-and-machine-intelligence/neural-nets-for-generating-music-f46dffac21c0
https://github.com/gauravtheP/Music-Generation-Using-Deep-Learning
https://github.com/Skuldur/Classical-Piano-Composer
https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5

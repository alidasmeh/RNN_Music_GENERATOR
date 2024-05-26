# Music Generator 
## by Recurrent Neural Network - using Keras 

This project is made as the first step for next projects. I have started working on AI and Music from 2017, specificly in Iranian music. In this project, I will use very same I will simply change the training dataset of this RNN to see how good it is compatible with Iranian music.

** Currently the dataset is  Essen Associative Code and Folksongs Database (http://www.esac-data.org/), German Folksongs (https://kern.humdrum.org/cgi-bin/browse?l=essen/europa). 
I am planning to create such a dataset for Iraninan Radif repertoire. **

Instruction: 
- This code consists three sections: 
    * Preprocessing Data
    * Train a Model : Building and Creating
    * Generate New Piece
- If you want to change the dataset, you need to train a model by that, it means you need to change the model.h5 file (or create another .h5 file for your dataset).
** Warning: Training a model with this datasets on local computer can be time and compute-consuming! **
If you want to train a model (creating a new .h5 file) you need to run "Preprocessing Data" cells and "Train a Model : Building and Creating" cells.
- If you already have .h5 file, you just need to run "Preprocessing Data" cells and "Generate New Piece" cells. At the end of the last code cell there is a variable which is called "seed". Seed is the very first motif you most provide for the algorithm to generate the piece of music based on.
At the end of this process there will be a MIDI file, you will find that MIDI file in the project to folder. You can open that MIDI everywhere you want. 


Many Thanks : https://www.youtube.com/watch?v=FLr0r-QhqH0

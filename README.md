# CS 7643 Final Project
 Final Project for Deep Learning containing models and data from the Comma AI dataset for longitudinal Behavior of Autonomous Vehicles


# Running the CNN-LSTM model
To run this model, open the CNN-LSTM model directory and start the jupyter notebook titled "comma_AI_Coles_Model.ipynb." This notebook contains everything needed for data extraction, data processing, training, and testing. Note that the 3 models designed in the notebook corresponds to different approaches to the problem. N2N_model1 is the model discussed in the final report. Training the model does not need to be done unless you would like to. This is because each model is saved in a .h5 file and their respective training history is also saved in a .npy file.

# Running the CNN-BGRU model
For the estimation of vehicle speed, open the file 'CNN-BGRU for speed.ipynb' and follow through those blocks to to deal with data preparation and training.
For the estimation of vehicle acceleration, open the file 'CNN-BGRU for acceleration.ipynb' and follow through those blocks to deal with data preparation and training.
There are a couple variants of the model, they share the same structure, but have different parameters. You can download the trained models using this link: https://gtvault-my.sharepoint.com/:u:/g/personal/azhou46_gatech_edu/EVgqE4V4sBZFjZpo84F47GgByJLUZyYSkyKEN1C7uJLhXw?e=WLUt5d. The block for loading and testing the trained model is right after the block of model training.

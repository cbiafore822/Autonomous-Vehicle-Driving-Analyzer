# Longitudnal Behavior of Autonomous Vehicles
 Deep Learning Project containing models and data from the Comma AI dataset for longitudinal behavior of Autonomous Vehicles


Traditional radar-based adaptive cruise controllers are outdated, and unfortunately most of them cannot navigate in low speed due to the limitation of the radar.  The state of the art in AV industry is switching to camera-based solutions thanks to the recent development in computer vision and deep learning. To understand the behavior of existing AVs that use vision-based longitudinal motion planning,this study attempts three different methods to retrofit the AV longitudinal driving  behavior  (i.e.,  estimating  the  vehiclespeed and acceleration given video input). After retrofitting, we  can  obtain  a  deep  neural  net  model  to  describe  howthose black-box AVs will react to ambient traffic.  We also present a custom longitudinal control model that shows the potential to implement different driving style or address any special needs on speed control.

# Running the CNN-LSTM model
To run this model, open the CNN-LSTM model directory and start the jupyter notebook titled "comma_AI_Coles_Model.ipynb." This notebook contains everything needed for data extraction, data processing, training, and testing. Note that the 3 models designed in the notebook corresponds to different approaches to the problem. N2N_model1 is the model discussed in the final report. Training the model does not need to be done unless you would like to. This is because each model is saved in a .h5 file and their respective training history is also saved in a .npy file.

# Running the CNN-BGRU model
For the estimation of vehicle speed, open the file 'CNN-BGRU for speed.ipynb' and follow through those blocks to to deal with data preparation and training.
For the estimation of vehicle acceleration, open the file 'CNN-BGRU for acceleration.ipynb' and follow through those blocks to deal with data preparation and training.
There are a couple variants of the model, they share the same structure, but have different parameters. You can download the trained models using this link: https://gtvault-my.sharepoint.com/:u:/g/personal/azhou46_gatech_edu/EVgqE4V4sBZFjZpo84F47GgByJLUZyYSkyKEN1C7uJLhXw?e=WLUt5d. The block for loading and testing the trained model is right after the block of model training.

# A custom AV model using our own driving data
Moreover,  we train a custom modelOP-hao using our own driving data.  The model elaboratesthat the besides retrofitting, the prediction of the speed andacceleration  is  another  promising  functionality  the  modelcan be extended.

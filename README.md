# SIT (Signal to Image Translation)
# Dataset
Used MATLAB to generate a dataset of 5000 image pairs by using variable feedback based Self Mixing Interferometry. 
 1. Added random Gaussian noise resulting in signal to noise ratio (SNR) varying from 20 dB to 34 dB. 
 2. The frequency range of the remote motion was set from 40 Hz to 2200 Hz while sampling frequency, was set to 100 KHz

Sample dataset consiting of Train, Test and validation set is in this repo.


For accessing full dataset from below url: 
https://drive.google.com/file/d/10OVBlOn4GtmDUdAHgHEqNHGv9fZS55J1/view?usp=sharing

Clone and follow the steps mentioned in the repo of GAN mentioned below and use this dataset:
https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix

# Install required libraries
Create an environment and install all the required libraries

# Training of model
python train.py --dataroot ./path_to_folder --name model_name --model pix2pix --direction AtoB --use_wandb

# Testing of model
python test.py --dataroot ./path_to_folder --direction AtoB --model pix2pix --name model_name --use_wandb


*Please note that this Page update is under process.*

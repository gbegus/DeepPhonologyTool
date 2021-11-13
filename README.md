
# Deep Phonology Tool

This tool allows you to train a fiwGAN or a ciwGAN 

## Create a Globus account  

[Globus](https://www.globus.org/) is a UChicago non-profit service for transferring files. You will use Globus to upload files for training.

To create a Globus account, follow these steps: 


To enable file transfer from your local computer, follow these steps: [instructions](https://docs.globus.org/how-to/get-started/).

- [Mac](https://docs.globus.org/how-to/globus-connect-personal-mac/)
- [Linux](https://docs.globus.org/how-to/globus-connect-personal-linux/)
- [Windows](https://docs.globus.org/how-to/globus-connect-personal-windows/)


## Fill out a Google form

 Fill out [this Google form](https://forms.gle/QAXmbq9UBsGbR1Uu9) where you set the hyperparameters of the model you wish to train and briefly describe your project. 
 
## Wait for review

Once you submit the Google form, we will review your request and set up your permissions in our high performance computing space. This might take a few days. We might not be able to approve all requests. 
 

## Prepare training data

All files for training need to be in .wav format with 16-bit quantization and 16kHz sampling rate. The model won't run unless the files are in the correct format. The files also generally need to be less than 1 s long.


## Upload training data 
 
1. Once you get permission, click on the link you received to your email. Alternatively, you can log into your Globus account and find the Deep Phonology Tool.
<img src="globus1.png" width="500">

Search for Deep Phonology Tool.

<img src="globus2.png" width="500">

2. Create a new folder in your directory and give it a title `/traindata/`. Upload your training files to `/traindata/`. 

<img src="globus3.png" width="500">

4. Fill out this form to start training.

## Get training checkpointss

You should see trained checkpoints in your directory soon after you submit the second Google form. The training will go on for 24-72 hours (on a K80, 1080Ti, or 2080Ti). If you need more time, you can resubmit the request. 

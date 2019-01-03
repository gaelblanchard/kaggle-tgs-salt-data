# kaggle-tgs-salt-data
Kaggle TGS Salt Identification Challenge Keras and PyTorch Application
* [Competition Website](https://www.kaggle.com/c/tgs-salt-identification-challenge)
* [The Public Leaderboard](https://www.kaggle.com/c/tgs-salt-identification-challenge/leaderboard) Search for Gael Blanchard
* Designed a nueral network that analyzed seismic imaging and generated segmentation masks representing salt deposits present within the image.
* Implemented Activations and Modules based off arxiv papers
* Finished in Top 13% beating out 2700+ competitors


# Technologies
* Keras, Pytorch, TensorFlow, Python

# In this repository
* The submission file (csv) that placed me in the top 13% of the public leaderboard.
* Pdf of a a complete run of my winning solution on google cloud server.
* A Kaggle notebook version of Pytorch implementation(1) and a Keras implementation(2).

# Links
* [Kaggle Notebook Keras Implementation](https://www.kaggle.com/gaelblanch/optimal-unet-beyond-a/code) 
  * Didn't have enough ram and gpu so switched to google cloud solution.
  * Shows the data preparation files that contributed to the notebook
* [Kaggle Notebook PyTorch Implementation](https://www.kaggle.com/gaelblanch/scorepytorch?scriptVersionId=7231838)
  * Primarily an alternative version of the nueral network for demonstrative purposes
  * Was done on multiple round of epochs




# Brief Overview
Several areas of Earth with large accumulations of oil and gas also have huge deposits of salt below the surface.

But unfortunately, knowing where large salt deposits are precisely is very difficult. Professional seismic imaging still requires expert human interpretation of salt bodies. This leads to very subjective, highly variable renderings. More alarmingly, it leads to potentially dangerous situations for oil and gas company drillers.

To create the most accurate seismic images and 3D renderings, TGS (the world’s leading geoscience data company) is hoping Kaggle’s machine learning community will be able to build an algorithm that automatically and accurately identifies if a subsurface target is salt or not.

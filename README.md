# EverybodyDanceNow
Motion Transfer, modified version by OrionChocoPie.
# Everybody Dance Now
The main difference between this repository and the others is the pipeline organized in notebooks that can be run in colab. For convenience, it will be necessary to connect google drive, where the data and models will be located.

At the beginning of each notebook you will need to change the paths to your convenience.

# First step
To start, run processing_dance_video.ipynb to generate a dataset from your video and process the video dances for transfer.

# Second step
Then run training.ipynb to train the model.

# Third step
Then run inference.ipynb to move the dance.

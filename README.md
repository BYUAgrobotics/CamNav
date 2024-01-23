# CamNav
Camera-based robot navigation

Author(s) - David Akagi (dcakagi@gmail.com)

Computer vision approaches for detecting/navigating the competition environment.

## camera_sensing.ipynb
Various approaches to detecting the edges of the planter boxes to produce motor commands for maneuvering the robot between planter rows. 

Images of the arena used in the Jupyter notebook are stored in the BYUAgRobotics Google Drive, along with a likely more current version of this notebook. If you don't have access to the the drive, get it before trying to run this notebook, or define a path to your own set of images.

### Running instructions
Open the notebook in Google Colab (https://colab.research.google.com/), probably while logged in as BYUAgRobotics.

Run the first cell to mount the BYUAgRobotics Google Drive, allowing photos to be retrieved from the Drive.

Run the rest of the cells to try the various line detection approaches. Play around with different blurring/line detection parameters to see what best works. Also get an idea of how sensitive these approaches are to lighting conditions and parameter selection.

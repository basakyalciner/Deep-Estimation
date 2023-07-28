# Monocular Camera Deep Map Estimation

This project aims to estimate depth maps of objects using a monocular camera. It consists of two main steps: In the first step, the dimensions between the camera and the object are estimated using the screen and camera angles; in the second step, a deep map is generated using the Midas library to estimate depth maps with a monocular camera.

Requirements

Python 3.x
OpenCV
Midas Library
Other dependencies (e.g., numpy)
## Step 1: Camera and Object Dimensioning

In this step, camera and screen angles are utilized to estimate the real dimensions of objects using a monocular camera. This step provides critical information for calculating the actual size of the object.

## Step 2: Monocular Camera Deep Map Estimation

In this step, we utilize the Midas library to generate depth maps with a monocular camera. Midas is a deep learning model trained for depth estimation

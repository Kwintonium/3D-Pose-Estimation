![Logo](https://i.morioh.com/210527/37109c82.webp)


# 3D Multi-Person Pose Estimation

In this project, I use Google's Movenet Multipose Lightning model from tf-hub to extract pixel locations human pose keypoints from a realtime image, and then I extract the 3D coordinates relative to the camera in object space using perspective geometry and stereo cameras. The cameras are calibrated using OpenCV in Python.

The purpose of this project is to determine where a person's bodypart is relative to a camera for 
## Viewing the Project

To see the code, please [click here](https://nbviewer.org/github/Kwintonium/3D-Pose-Estimation/blob/main/main.ipynb).

## Documenation

[Google's Lightning 1 Movenet Model](https://tfhub.dev/google/movenet/multipose/lightning/1)

[How Stereo Vision Works](https://www.cse.unr.edu/~bebis/CS791E/Notes/StereoCamera.pdf)
## Authors

- [@Quinn Meyer](https://www.github.com/kwintonium)


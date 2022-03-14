# optical_flow_tracking_on_recorded_video

Computer Vision is one of the most leading domains in the field of Artificial Intelligence. It enables the machines to see, observe and understand.
This project work is an overview of how to implement Optical Flow Algorithms on a pre-recorded video using all the necessary libraries and functions from OpenCV.

# Optical Flow

Optical Flow is a method of calculating the displacement of brightness patterns from one frame to the next. This is accomplished by combining the intensity levels of adjacent pixels.
It is a term used to describe how an object in an image moves. It's commonly used to describe a sequence of pictures with a little time gap between them, such as video frames. 
Optical flow determines the velocity of points inside pictures and predicts where points could appear in the future image sequence.

## Types of Optical Flow

  1. Sparse Optical Flow - Lucas Kanade Method
  2. Dense Optical Flow - Gunnar Farneback Method

## Sparse Optical Flow

Sparse optical flow algorithms estimate the displacement for a selected number of pixels in the given image. Sparse Optical Flow algorithms assume local smoothness. 
This provides more robustness to noise but offers a much sparser flow field.

## Dense Optical Flow

Dense Optical Flow computes the optical flow vector for each and every pixel present in the frame. 
Due to the involvement of every pixel, the computational speed is comparatively very high making the algorithm slow. However, the results obtained are accurate.

# Open CV

OpenCV (Open-Source Computer Vision Library) is an open-source BSD-licensed library that includes several hundreds of computer vision algorithms. 
OpenCV has a modular structure, which means that the package includes several shared or static libraries.

# Steps:
  1. Install OpenCV using PIP
 
         pip install opencv-python
         
  2. Download a random pre-recorded video (prefereably with moving traffic for good understanding)
  3. In order to perform Sparse Optical Flow, Run the __*"sparse_optical_flow.py"*__ python file.
  4. Don't forget to specify the path of the downloaded video in the __*cv.VideoCapture*__ (" <specify path here> ")
  5. Follow the same procedure for performing Dense Optical Flow algorithm.
  
  
  
# Result
  
## Sparse Optical Flow Algorithm
  
![alt text](https://github.com/vishal-kasyap/optical_flow_tracking_on_recorded_video/blob/main/optical_flow_tracking_on_recorded_video/sparse_optical_flow.png "Sparse Optical Flow")
  
## Dense Optical Flow Algorithm
  
![alt text](https://github.com/vishal-kasyap/optical_flow_tracking_on_recorded_video/blob/main/optical_flow_tracking_on_recorded_video/dense_optical_flow.png "Sparse Optical Flow")

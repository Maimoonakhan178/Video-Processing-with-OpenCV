# Video-Processing-with-OpenCV
This Python script demonstrates basic video processing techniques using the OpenCV library. It reads a video file, applies different image processing algorithms to its frames, and saves the processed frames to a new video file.

Prerequisites
Before running the script, make sure you have the following installed:

Python 3.x
OpenCV library (opencv-python)
You can install OpenCV using pip:


pip install opencv-python
Usage
Clone the repository or download the Python script.
Make sure you have a video file in a compatible format. The script currently expects the video file path to be C:\\Users\\spring2018\\Downloads\\karate.mp4. You can modify this path in the script to point to your own video file.
Run the Python script.
Description
The script performs the following operations:

Read Video: It reads the input video file using OpenCV's VideoCapture.
Process Frames: For each frame in the video:
If the frame index is less than the midpoint of the video, it applies the Canny edge detection algorithm to detect edges.
If the frame index is greater than or equal to the midpoint, it applies the Harris corner detection algorithm to detect corners.
Write Processed Frames: It writes the processed frames to a new video file using OpenCV's VideoWriter.
Customization
You can customize the script according to your requirements:

Change the input video file path.
Adjust the parameters of the image processing algorithms (Canny edge detection and cornerHarris corner detection) to achieve different effects.
Modify the output video file format and properties (codec, frame rate, resolution) as needed.

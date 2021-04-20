# OpenCV-Import-Video
## Play a video using OpenCV
### OpenCV (Open Source Computer Vision):
is a computer vision library that contains various functions to perform operations on Images or videos. OpenCV library can be used to perform multiple operations on videos. Let’s see how to play a video using the OpenCV Python.
To capture a video, we need to create a VideoCapture object. VideoCapture have the device index or the name of a video file. Device index is just the number to specify which camera. If we pass 0 then it is for first camera, 1 for second camera so on. We capture the video frame by frame.

#### Syntax:

cv2.VideoCapture(0): Means first camera or webcam.
cv2.VideoCapture(1):  Means second camera or webcam.
cv2.VideoCapture("file name.mp4"): Means video file

### Steps to Install OpenCV on Windows
1.	Install Python on your system
2.	Install pip
3.	Install OpenCV library using pip

### Reading a Video:
In OpenCV, a video can be read either by using the feed from a camera connected to a computer or by reading a video file. The first step towards reading a video file is to create a VideoCapture object. Its argument can be either the device index or the name of the video file to be read.

### Displaying a video
After reading a video file, we can display the video frame by frame. A frame of a video is simply an image and we display each frame the same way we display images, i.e., we use the function cv2.imshow().


https://user-images.githubusercontent.com/80674012/115386849-8ed12f80-a1f7-11eb-89f1-3684d82dbce8.mp4

### Show Video in Multiple Frame

### Multiple Video in One Frame

### Blog Site: 
https://www.smiit.xyz/opencv-import-videos/

### GitHub Link:
https://github.com/SMIIT-Projects/OpenCV-Import-Video

### Tools and Technologies:
The Code is written in Python 3.8.5.

### Used libraries:
opencv-python==4.5.1.48
matplotlib==3.4.1
numpy==1.20.2
pandas==1.2.4
scipy==1.6.2
seaborn==0.11.1


Thank You!


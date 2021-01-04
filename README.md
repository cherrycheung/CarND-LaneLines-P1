# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="test_images_output/solidYellowCurve2.jpg" width="550" alt="Combined Image" />
<img src="test_images_output/solidWhiteRight.jpg" width="550" alt="Combined Image" />

---

### Finding Lane Lines on the Road

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road

---
### Pipeline
My pipeline consists of a couple of steps in order to add lane lines on the original image:
1. The image is converted to grayscale
2. Use Canny edge detection in a defined region of interest to find edges
3. Use Hough transform to find lane segments

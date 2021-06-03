## Tennis Ball Tracking using OpenCV and Python

### Room Lighting

![room](https://user-images.githubusercontent.com/75261680/131233402-46a6e571-46d4-43f9-825d-f06948dcfd11.gif)

### Sunlight

![sun](https://user-images.githubusercontent.com/75261680/131233552-58672265-cb5b-4747-ae58-a96956769ccc.gif)

### Torchlight

![torch](https://user-images.githubusercontent.com/75261680/131233556-670770f7-7ce8-44e1-9ebf-6576c026df44.gif)



#### Steps invovled
* Filter out the noise using a median blur
* Convert the colorspace to grayscale for Adaptive Thresholding
* Convert the colorspace separately to LAB and applying Histogram Equalisation on the L channel
* Obtaining a bitmask using bitwise operations
* Feeding the bitmask to Hough Circles inorder to obtain circular contours

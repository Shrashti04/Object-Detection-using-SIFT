# Object-Detection-using-SIFT
Implemented SIFT from scratch and use it between images for object finding/identification. Apart from object identification, we’ve applied the algorithm for similarity detection as well on live images taken from camera.
This repository contains Python code for detecting and matching Scale-Invariant Feature Transform (SIFT) keypoints in images using scratch and comparing with OpenCV library as well as did template matching. For application, did real time detection.

## Requirements for setup
Make sure this these things should be include in your system:<br>
    1. Python 3.x\
    2. OpenCV\
    3. NumPy\
    4. Matplotlib

## Usage
1. Install the required dependencies:\
`pip install numpy opencv-python matplotlib`
2. Clone the repository:\
`git clone https://github.com/Shrashti04/Object-Detection-using-SIFT.git`
3. Navigate to the repository directory:\
`cd Object-Detection-using-SIFT`
4. Place your query image and scene image in the repository directory.
5. Run the main script:\
`python SIFT.py`
6. View the output: <br>
If enough matches are found, the script will display the scene image with the detected object highlighted.
If not enough matches are found, a message will be printed indicating the insufficient matches.

## Output Images

### Using Scratch
_Keypoints_:

![coke keypoints](https://github.com/Shrashti04/Object-Detection-using-SIFT/assets/104893904/0e24955a-6725-417b-97df-9d5d84e8a660)

_Keymatching and detecting the object_:

![from scratch](https://github.com/Shrashti04/Object-Detection-using-SIFT/assets/104893904/8b31077a-308d-43d3-964e-ed470989c46d)

### Using OpenCV
_Keypoints and matching_:

![from opencv](https://github.com/Shrashti04/Object-Detection-using-SIFT/assets/104893904/8d31c0bb-960f-4952-a2f8-8a343d00ed7a)

## Other examples of object detection
![lock found](https://github.com/Shrashti04/Object-Detection-using-SIFT/assets/104893904/e24a0348-5ace-447a-9c43-510ebcf18ded)
![what found](https://github.com/Shrashti04/Object-Detection-using-SIFT/assets/104893904/76b03986-8410-4b1d-ae96-f116ff5053e1)

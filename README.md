# Social Distance Monitoring 

## Objective:

The objective of the project is to develop algorithm to monitor the social distancing for a given recorded video or live feed as input.
Once the video is analyzed, system should display number of violations and percentage of violation of social distancing in a frame.

## Methodology:

We have developed two algorithm to detect the social distancing for provided input.
1. HOG - Histogram of Oriented Gradients
2. DNN - Deep Convolution Neural Network

## Tools and Packages:

### Language:
1. Python3.0 or above

### Packages:
1. OpenCV
2. Numpy
3. TensorFlow
4. Imutils
5. Object_detection

During installation if you ran into any problem and face any below errors, try below said methods.

1) <code>!pip install pycocotools</code>

if this errors out with "ERROR: Command errored out with exit status 1:" or 
"error: Microsoft Visual C++ 14.0 is required. Get it with "Build Tools for Visual Studio": https://visualstudio.microsoft.com/downloads/"

try downloading: https://visualstudio.microsoft.com/downloads/
 

2) pip install tensorflow-object-detection-api
ERROR: readme-renderer 26.0 has requirement bleach>=2.1.0, but you'll have bleach 1.5.0 which is incompatible.

try installing: pip install bleach -U --bleach==2.1.0


## How to execute algorithms
Run the python file provided. In case of any change in the input video, update the path of the input video and perform execution of python script.

## Sample input and output
We have provided both input and output(processed) videos for reference.

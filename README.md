# opencv_python_examples
Opencv examples with implementation in python

Welcome to a tutorial series, covering OpenCV, which is an image and video processing library with bindings in C++, C, Python, and Java. OpenCV is used for all sorts of image and video analysis, like facial recognition and detection, license plate reading, photo editing, advanced robotic vision, optical character recognition, and a whole lot more.

We will be working through many Python examples here. Getting started with OpenCV's Python bindings is actually much easier than many people make it out to be initially. You will need two main libraries, with an optional third: python-OpenCV, Numpy, and Matplotlib.

Windows Users:
python-OpenCV - There are alternative methods, but this is the easiest. Download the appropriate wheel (.whl) file, and install using pip. See video for help.

pip install numpy

pip install matplotlib

Not familiar with using pip? See the Pip installation tutorial for help.

Linux / Mac Users:
pip3 install numpy or apt-get install python3-numpy. You may need to apt-get install python3-pip.

pip3 install matplotlib or apt-get install python3-matplotlib.

apt-get install python-OpenCV.

Matplotlib is an optional choice for displaying frames from video or images. We will show a couple of examples using it here. Numpy is used for all things "numbers and Python." We are mainly making use of Numpy's array functionality. Finally, we are using the python-specific bindings for OpenCV called python-OpenCV.

There are some operations for OpenCV that you will not be able to do without a full installation of OpenCV (about 3GB in size), but you can actually do quite a bit with the fairly minimal installation of python-OpenCV. We will wind up using the full installation of OpenCV later in this series, so you can feel free to get it if you like, but these 3 modules will keep us busy for a while!

Make sure your installations were successful by running Python, and doing:

import cv2
import matplotlib
import numpy
If you get no errors, then you are ready to go. Ready? Let's dive off the deep-end!



credits : Harrison , Python Programmer.

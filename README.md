# Cuda-Fractal
 Cuda accelerated Python scripts for Fractal MadelBrot images and video<br>
 + ![Board](/output/MandelZoom2.png?raw=false)<BR>
## Description
Python script is made for Jupyter Labs: <BR>
Clicker : click and zoom into Mandelbrot .<BR>
Streamer : Video zoomer into Mandelbrot .<BR>
Grower : Using distorted fractal function, select area of interest, then let it grow .<BR>
## Fractal functions
Read python Scripts and adapt the base functions to your need<br>
Many variations are tested and pre-defined (just unmark the right one<br>
## Dependencies:
import os <br>
import cv2 <br>
from datetime import datetime <br>
import numba <br>
from numba import jit  <-------- Cuda required> <br>
import numpy as np <br>
import random <br>
import scipy as sc <br>
import math <br>
from numpy.random import default_rng <br>
import cmath <br>
from numba import cuda <----------- Cuda required> <br> <br>
+ ![Board](/output/MandelZoom11.png?raw=false)<BR>





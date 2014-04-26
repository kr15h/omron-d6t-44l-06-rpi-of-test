Omron D6T-44L-06 test application
=================================

Testing the sensor with openFrameworks on the Raspberry Pi. This should display a 4x4 grid with colored rectangles.

I used I2C C functions by Scott Ellis and a C++ class for Omron D6T sensors by JoMu. A zip file can be found in the following [link](http://www.raspberrypi.org/forums/viewtopic.php?f=44&t=47465))

To compile, cd to your openFrameworks apps folder on your Raspberry Pi, git clone this repo, copy oF Makefile in there, cd in the project folder and issue make && make run. Your sensor should be connected by then.

# rpi-jessie-opencv3.2
Dockerfile to create a container for Raspberry Pi with jessie and opencv3.2

Extension of the resin.io Raspberry Pi base image (jessie) with OpenCV 3.2 libraries and python 2.7 bindings added. Installation based upon instructions from:
http://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/

To build:

    docker build -ti rpi-jessie-opencv3.2 .

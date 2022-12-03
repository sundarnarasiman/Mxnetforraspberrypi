# Mxnetforraspberrypi
This repository contains insturctions to use cross-compiled and ready to use executable for the running Mxnet 1.0.0 on Raspberry PI (Arm) processors.
## Instructions
Please follow these instructions:-

### a)Install the pre-requisits below
sudo apt-get update
sudo apt-get -y install git cmake build-essential g++-4.8 c++-4.8 liblapack* libblas* libopencv* libclas*
sudo apt-get install libatlas-base-dev
    
### b)Download the compiled executable for Armv7 from S3
wget https://s3.amazonaws.com/mxnet4raspberrry/mxnet.zip

### c)Unzip the contents of mxnet.zip
unzip mxnet.zip

### d)Navigate to python folder under mxnet
  cd mxnet/python
  
### e)pip install --upgrade pip

### f)sudo pip install -e .

### This ends the instruction

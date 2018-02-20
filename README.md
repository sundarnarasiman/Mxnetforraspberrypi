# Mxnetforraspberrypi
This repository contains insturctions to use cross-compiled and ready to use executable for the running Mxnet 1.0.0 on Raspberry PI (Arm) processors.
## Instructions
Please follow these instructions
a)Download the compiled executable for Armv7 from S3
wget https://s3.amazonaws.com/mxnet4raspberrry/mxnet.zip

b)Unzip the contents of mxnet.zip
unzip mxnet.zip

c)Navigate to python folder under mxnet
  cd mxnet/python
d)pip install --upgrade pip

e)sudo pip install -e .

# TensorFlow-1.4_Jetson-TX2
Pre-build wheel file for installing TensorFlow 1.4 on Jetson TX2

# Installation
For now TensorFlow is only build for Jetson TX2 with Python 2.7.

Install using the following commands:
```
$ git clone https://github.com/JesperChristensen89/TensorFlow-1.4_Jetson-TX2.git
$ cd TensorFlow-1.4_Jetson-TX2
$ sudo apt-get install -y python-pip python-dev
$ sudo pip install file```

# Build information
TensorFlow 1.4 is build on Jetson TX2 with the environment:
* L4T 28.1 (JetPack 3.1)
* CUDA 8.0
* cuDNN 6.0.21
TensorFlow:
* Version 1.4
* Build with CUDA support

Build from source by modifying the guide from https://github.com/jetsonhacks/installTensorFlowTX2 and TensorFlow docs.

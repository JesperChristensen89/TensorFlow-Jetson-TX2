# TensorFlow-Jetson-TX2
Pre-built wheel files for installing TensorFlow on Jetson TX2.
Currently built version include TensorFlow 1.3 and 1.5.

# Installation
For now TensorFlow is only built for Jetson TX2 with Python 2.7.

Install using the following commands:
```
$ git clone https://github.com/JesperChristensen89/TensorFlow-Jetson-TX2.git
$ cd TensorFlow-Jetson-TX2
$ sudo apt-get install -y python-pip python-dev
$ sudo pip install file
```

# Build information
TensorFlow 1.3 is built on Jetson TX2 with the environment:
* L4T 28.1 (JetPack 3.1)
* CUDA 8.0
* cuDNN 6.0.21

TensorFlow 1.5 is built on Jetson TX2 with the environment:
* L4T 28.1 (JetPack 3.2)
* CUDA 9.0
* cuDNN 7.0.5 RC

Built from source by modifying the guide from https://github.com/jetsonhacks/installTensorFlowTX2 and https://www.tensorflow.org/install/install_sources.

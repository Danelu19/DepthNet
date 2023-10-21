<img src="https://github.com/dusty-nv/jetson-inference/raw/master/docs/images/deep-vision-header.jpg" width="100%">

# Deploying Deep Learning
Welcome to our instructional guide for inference and realtime vision [DNN library](#api-reference) for **[NVIDIA Jetson](https://developer.nvidia.com/embedded-computing)** devices.  This project uses **[TensorRT](https://developer.nvidia.com/tensorrt)** to run optimized networks on GPUs from C++ or Python, and PyTorch for training models.

#### System Setup

* [Setting up Jetson with JetPack](docs/jetpack-setup-2.md)
* [Running the Docker Container](docs/aux-docker.md)
* [Building the Project from Source](docs/building-repo-2.md)

#### Inference

* [Monocular Depth](docs/depthnet.md)

## API Reference

Below are links to reference documentation for the [C++](https://rawgit.com/dusty-nv/jetson-inference/master/docs/html/index.html) and [Python](https://rawgit.com/dusty-nv/jetson-inference/master/docs/html/python/jetson.html) libraries from the repo:

#### jetson-inference

| Monocular Depth    | [`depthNet`](https://rawgit.com/dusty-nv/jetson-inference/master/docs/html/group__depthNet.html#classdepthNet) | [`depthNet`](https://rawgit.com/dusty-nv/jetson-inference/master/docs/html/python/jetson.inference.html#depthNet) |

#### jetson-utils

* [C++](https://rawgit.com/dusty-nv/jetson-inference/master/docs/html/group__util.html)
* [Python](https://rawgit.com/dusty-nv/jetson-inference/master/docs/html/python/jetson.utils.html)

These libraries are able to be used in external projects by linking to `libjetson-inference` and `libjetson-utils`.

## Code Examples

Additional C++ and Python samples for running the networks on images and live camera streams can be found here:

|                   | C++              | Python             |
|-------------------|---------------------|---------------------|
| &nbsp;&nbsp;&nbsp;Monocular Depth    | [`depthnet.cpp`](examples/depthnet/segnet.cpp) | [`depthnet.py`](python/examples/depthnet.py) |


</details>

##
<p align="center"><sup>© 2016-2019 NVIDIA | </sup><a href="#deploying-deep-learning"><sup>Table of Contents</sup></a></p>


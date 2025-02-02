# Ubicoders Update
- ZED PYTHON API: pyzed DOES NOT support GPU


# Stereolabs ZED - OpenCV Python

This sample is the perfect place to get started coding with the ZED and OpenCV. It shows how to:

  - Capture image, depth and point cloud from the ZED.
  - Convert image and depth map to compatible 32-bits float OpenCV matrix.
  - Display video and depth with OpenCV.
  - Adjust several depth parameters: depth sensing mode, quality, units, resolution.
  - Save side by side image, depth image and point cloud in various formats

## Getting started

- First, download the latest version of the ZED SDK on [stereolabs.com](https://www.stereolabs.com).
- For more information, read the ZED [API documentation](https://www.stereolabs.com/developers/documentation/API/).

### Prerequisites

- Windows 7 64bits or later, Ubuntu 16.04 or 18.04
- [ZED SDK](https://www.stereolabs.com/developers/) and its dependencies ([CUDA](https://developer.nvidia.com/cuda-downloads), [OpenCV](https://github.com/opencv/opencv/releases))
- [ZED Python API](https://github.com/stereolabs/zed-python-api), check the README of the github to know how to install it

## Run the program

Open a termial and simply execute the python script.

### Windows
```
python zed_opencv.py [path to SVO file]
```

### Linux
```
python3 zed_opencv.py [path to SVO file]
```

You can optionally provide an SVO file path (recorded stereo video of the ZED)

### Keyboard shortcuts

This table lists keyboard shortcuts that you can use in the sample application.

Parameter             | Description                   |   Hotkey
---------------------|------------------------------------|-------------------------------------------------
Save Side by Side      | Save side by side image.       |   's'
Save Depth             | Save depth image.              |   'p'
Save Point Cloud       | Save 3D point cloud.        |   'd'
Switch cloud format    | Toggle between point cloud formats.    |   'm'
Switch depth format    | Toggle between depth image formats. |   'n'                                                
Exit         | Quit the application.             | 'q'

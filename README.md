# SelfBuilds_macOS_arm64  
Here are some pre-built frameworks, tools, python packages for Apple Silicon (macOS ARM64).  

|  Name  |         Xcode Frameworks          |      Python3 Packages       |    Pre-built Binaries    |
| :----: | :-------------------------------: | :-------------------------: | :-----------------------:|
| OpenCV | *[Download][opencv.xcframeworls]* | *[Download][opencv-python]* | ~~*[Download][opencv]*~~ |
|   Qt   |                                   |    *[Download][pyside6]*    |     *[Download][qt]*     |  

* [OpenCV](https://github.com/SloneWang/SelfBuilds_macOS_arm64#opencv)  
* [Qt](https://github.com/SloneWang/SelfBuilds_macOS_arm64#qt)  

## OpenCV  

### Xcode Frameworks *[Download][opencv.xcframeworls]*  
> opencv2.xcframework  
> Version: 4.5.1  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Xcode 12.4  

Platforms and architectures:  
  * iOS: arm64, armv7  
  * iOS Simulator: x86_64, arm64  
  * macOS: x86_64, arm64  
  * Mac Catalyst: x86_64, arm64  

### Python3 Packages *[Download][opencv-python]*  
> opencv-python  
> Version: 4.5.1.48  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Command Line Tools for Xcode 12.4  
  * Python 3.8.2 (included in Command Line Tools)  
  * numpy 1.18.5 (See installation)  

Platforms and architectures:  
  * macOS: arm64  

Installation:  
  1. Download [tensorflow_macos-0.1alpha3.tar.gz][apple.numpy] and extract;  
  2. Open Terminal.app, and run `cd extract_dir/tensorflow_macos/arm64`;  
  3. Activate a python virtual environments (Optional), and run `pip install numpy-1.18.5-cp38-cp38-macosx_11_0_arm64.whl`;  
  4. Download this, goto download_dir, and run `pip install opencv_python-4.5.1.48-cp38-cp38-macosx_11_0_arm64.whl`  

### ~~Pre-built Binaries with Extra Modules *[Download][opencv]*~~  
> opencv  
> opencv_contrib Included  
> Dynamic Link Libraries  
> Python2.7 Supported  
> Python3.X Unsopported  
> Java Unsopported  
> Version: 4.5.1  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Xcode 12.4  

Platforms and architectures:  
  * macOS: arm64  

## Qt  

### Python3 Packages *[Download][pyside6]*  
> PySide6, shiboken6, shiboken6-generator  
> Version: 6.0.1  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Command Line Tools for Xcode 12.4  
  * Python 3.8.2 (included in Command Line Tools)   

Platforms and architectures:  
  * macOS: arm64  

Installation:  
  1. Download, and extract;  
  2. Open Terminal.app in the directory, and run `pip install *.whl`  

### Pre-built Binaries *[Download][qt]*  
> qt  
> Version: 6.0.1  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Xcode 12.4  

Platforms and architectures:  
  * macOS: arm64  









[^_^]:Links
[^_^]:OpenCV
[opencv.xcframeworls]:https://github.com/SloneWang/SelfBuilds_macOS_arm64/releases/download/opencv451/opencv2.xcframework.7z
[opencv-python]:https://github.com/SloneWang/SelfBuilds_macOS_arm64/releases/download/opencv451/opencv_python-4.5.1.48-cp38-cp38-macosx_11_0_arm64.whl
[opencv]:https://github.com/SloneWang/SelfBuilds_macOS_arm64/releases/download/opencv451/OpenCV-4.5.1-macosx_11_0_arm64.7z
[apple.numpy]:https://github.com/apple/tensorflow_macos/releases/download/v0.1alpha3/tensorflow_macos-0.1alpha3.tar.gz
[^_^]:Qt
[pyside6]:https://github.com/SloneWang/SelfBuilds_macOS_arm64/releases/download/qt601/PySide-6.0.1-cp38-macosx_11_0_arm64.7z
[qt]:https://github.com/SloneWang/SelfBuilds_macOS_arm64/releases/download/qt601/Qt-6.0.1-macosx_11_0_arm64.7z
